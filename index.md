---
layout: default
title: Home
---

<div class="home-shell">
  <section class="hero-card">
    <div class="hero-grid">
      <div class="hero-copy">
        <p class="eyebrow">Personal site / Hangzhou</p>
        <h1>Triston Lee</h1>
        <p class="hero-lead">
          我把这里当作一个公开工作台，用来记录 AI 系统、软件实验、以及仍在形成中的想法。
        </p>
        <p class="hero-text">
          这不是一份静态简历，而是一块持续更新的现场笔记：做过什么、正在验证什么、为什么值得继续做下去。
        </p>
        <div class="button-row">
          <a class="button button-primary" href="{{ '/about/' | relative_url }}">了解更多</a>
          <a class="button button-secondary" href="https://github.com/triston-lee">GitHub</a>
          <a class="button button-secondary" href="{{ '/writing/' | relative_url }}">最近文章</a>
        </div>
      </div>
      <aside class="hero-side">
        <img class="avatar" src="https://avatars.githubusercontent.com/u/55876861?v=4" alt="Portrait of Triston Lee">
        <div class="stat-stack">
          <div class="stat-card">
            <span class="stat-label">Base</span>
            <strong>Hangzhou, China</strong>
          </div>
          <div class="stat-card">
            <span class="stat-label">Focus</span>
            <strong>AI tooling, retrieval, product experiments</strong>
          </div>
          <div class="stat-card">
            <span class="stat-label">Motto</span>
            <strong>Es gibt keine Tatsachen, nur Interpretationen.</strong>
          </div>
        </div>
      </aside>
    </div>
  </section>

  <section class="section-card">
    <div class="section-heading">
      <p class="eyebrow">What I care about</p>
      <h2>把系统真正做出来，而不是只停留在概念里</h2>
    </div>
    <div class="pillars">
      <article class="pillar">
        <h3>AI Systems</h3>
        <p>关注 agent、检索增强、模型工作流，以及这些东西如何从 demo 变成可用系统。</p>
      </article>
      <article class="pillar">
        <h3>Readable Software</h3>
        <p>偏爱结构清晰、文档友好、可持续维护的代码，而不是一次性的技术炫技。</p>
      </article>
      <article class="pillar">
        <h3>Public Notes</h3>
        <p>把过程写下来。写作既是记录，也是对思路和判断标准的再校验。</p>
      </article>
    </div>
  </section>

  <section class="section-card">
    <div class="section-heading">
      <p class="eyebrow">Selected Work</p>
      <h2>最近公开可见的一些项目</h2>
    </div>
    <div class="project-grid">
      <article class="project-card">
        <div class="project-meta">TypeScript / Product Engineering</div>
        <h3><a href="https://github.com/triston-lee/odyverse">Odyverse</a></h3>
        <p>一个持续迭代中的 AI 原生产品方向，用来实验更连贯的搜索、组织和交互方式。</p>
      </article>
      <article class="project-card">
        <div class="project-meta">Python / Research Prototype</div>
        <h3><a href="https://github.com/triston-lee/agentic-rl">agentic-rl</a></h3>
        <p>围绕 Agentic RL 的实验项目，关注 agent 行为、反馈循环和策略优化。</p>
      </article>
      <article class="project-card">
        <div class="project-meta">TypeScript / Dev Tooling</div>
        <h3><a href="https://github.com/triston-lee/claude-code">claude-code</a></h3>
        <p>围绕 Claude Code 的工程化实践与可运行版本整理，强调可执行性和稳定性。</p>
      </article>
    </div>
  </section>

  <section class="section-card">
    <div class="section-heading">
      <p class="eyebrow">Writing</p>
      <h2>最近写下来的东西</h2>
    </div>
    {% if site.posts.size > 0 %}
      <div class="post-grid">
        {% for post in site.posts limit:3 %}
          <article class="post-card">
            <p class="post-date">{{ post.date | date: "%Y.%m.%d" }}</p>
            <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
            <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 150 }}</p>
          </article>
        {% endfor %}
      </div>
    {% else %}
      <p class="empty-state">第一篇文章还在路上，但这个站点已经开始记录过程了。</p>
    {% endif %}
  </section>
</div>
