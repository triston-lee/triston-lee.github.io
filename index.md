---
layout: default
title: Home
---

<div class="home-shell">
  <section class="hero-card personal-card">
    <div class="personal-card-grid">
      <div class="hero-copy">
        <p class="eyebrow">Personal Card / Hangzhou</p>
        <h1>Triston Lee</h1>
        <p class="profile-role">做 AI 系统，也写公开笔记。</p>
        <p class="hero-lead">
          我现在住在杭州，平时主要做 AI 系统、开发者工具，也会反复琢磨检索和知识组织这类问题。
        </p>
        <div class="tag-row">
          <span class="tag-chip">AI Systems</span>
          <span class="tag-chip">Dev Tooling</span>
          <span class="tag-chip">Retrieval</span>
          <span class="tag-chip">Public Notes</span>
        </div>
        <div class="button-row">
          <a class="button button-primary" href="https://github.com/triston-lee">访问 GitHub</a>
          <a class="button button-secondary" href="{{ '/projects/' | relative_url }}">查看项目</a>
          <a class="button button-secondary" href="{{ '/writing/' | relative_url }}">查看文章</a>
        </div>
      </div>
      <aside class="hero-side identity-rail">
        <div class="identity-frame">
          <img class="avatar" src="https://avatars.githubusercontent.com/u/55876861?v=4" alt="Portrait of Triston Lee">
          <div class="identity-meta">
            <p class="identity-name">Triston Lee</p>
            <p class="identity-location">Hangzhou, China</p>
          </div>
        </div>
        <div class="identity-stack">
          <article class="identity-card">
            <span class="stat-label">Now</span>
            <strong>在做 AI 原生产品，也在持续试 agent workflow 和工具链。</strong>
          </article>
          <article class="identity-card">
            <span class="stat-label">Approach</span>
            <strong>先做能跑的版本，再慢慢把结构、表达和杠杆感打磨清楚。</strong>
          </article>
          <article class="identity-card">
            <span class="stat-label">Find Me</span>
            <strong><a href="https://github.com/triston-lee">github.com/triston-lee</a></strong>
          </article>
        </div>
      </aside>
    </div>
  </section>

  <section class="section-card homepage-board">
    <div class="section-heading">
      <p class="eyebrow">Start Here</p>
      <h2>从这里继续看</h2>
    </div>
    <div class="homepage-grid">
      <article class="board-card">
        <p class="project-meta">About</p>
        <h3>关于我</h3>
        <p>如果你想先快速了解我是谁、我关注什么、我怎么工作，从这里开始最合适。</p>
        <a class="text-link" href="{{ '/about/' | relative_url }}">进入 About</a>
      </article>

      <article class="board-card" id="projects">
        <p class="project-meta">Projects</p>
        <h3>项目</h3>
        <p>公开项目会统一整理在这里，包括正在做的系统实验和已经能公开展示的工作。</p>
        <a class="text-link" href="{{ '/projects/' | relative_url }}">进入项目页</a>
      </article>

      <article class="board-card" id="writing">
        <p class="project-meta">Writing</p>
        <h3>文章</h3>
        <p>写作部分会放项目过程、阶段性判断，以及那些我希望以后还能回头看的东西。</p>
        <a class="text-link" href="{{ '/writing/' | relative_url }}">进入文章页</a>
      </article>
    </div>
  </section>

  <section class="section-card contact-card" id="contact">
    <div class="section-heading">
      <p class="eyebrow">Contact</p>
      <h2>联系与外部入口</h2>
    </div>
    <div class="contact-grid">
      <div>
        <p class="contact-lead">最直接的入口还是 GitHub。公开项目、代码和后续更新，我基本都会先放在那里。</p>
      </div>
      <div class="contact-links">
        <a href="https://github.com/triston-lee">GitHub</a>
        <a href="{{ '/about/' | relative_url }}">About</a>
        <a href="{{ '/projects/' | relative_url }}">Projects</a>
        <a href="{{ '/writing/' | relative_url }}">Writing</a>
      </div>
    </div>
  </section>
</div>
