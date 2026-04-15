# Triston Lee

一个基于 `Jekyll + GitHub Pages` 的个人主页仓库，包含首页、关于页、文章列表页和基础博客能力。

## 本地预览

1. 安装 Ruby 和 Bundler
2. 执行 `bundle install --path vendor/bundle`
3. 执行 `bundle exec jekyll serve`
4. 打开 `http://127.0.0.1:4000`

## 发布方式

1. 推送到 `main`
2. 在 GitHub 仓库 `Settings -> Pages` 中选择 `Deploy from a branch`
3. 分支选择 `main`，目录选择 `/ (root)`
4. 访问 `https://triston-lee.github.io`

## 内容维护

- 站点配置在 `_config.yml`
- 首页在 `index.md`
- 关于页在 `about.md`
- 文章列表页在 `writing.md`
- 新文章放在 `_posts/`，文件名格式为 `YYYY-MM-DD-title.md`
