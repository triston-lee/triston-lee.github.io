# triston-lee.github.io

Triston Lee 的个人主页源码仓库，使用 `Jekyll + GitHub Pages` 构建和发布。

这不是某个项目的官方站点，也不是通用模板仓库说明；它就是当前个人主页的实际源代码，包含首页、关于页、项目页和文章页。

## 站点内容

- 首页：个人名片式入口页
- `About`：个人简介和工作方式
- `Projects`：公开项目索引
- `Writing`：文章列表
- `_posts/`：博客文章内容

## 本地开发

1. 确保本机安装 Ruby 和 Bundler
2. 安装依赖：

```bash
bundle install --path vendor/bundle
```

3. 启动本地预览：

```bash
bundle exec jekyll serve
```

4. 打开 `http://127.0.0.1:4000`

如果 `4000` 端口已被占用，可以改用：

```bash
bundle exec jekyll serve --port 4001
```

## 发布

这个仓库通过 GitHub Pages 发布。

1. 推送到 `main`
2. 在 GitHub 仓库 `Settings -> Pages` 中选择 `Deploy from a branch`
3. 分支选择 `main`，目录选择 `/ (root)`
4. 发布地址：`https://triston-lee.github.io`

## 主要文件

- `_config.yml`：站点配置
- `index.md`：首页
- `about.md`：关于页
- `projects.md`：项目页
- `writing.md`：文章列表页
- `assets/style.css`：全站样式
- `_includes/custom-head.html`：额外 head 资源

## 写文章

在 `_posts/` 下新增 Markdown 文件，命名格式为：

```text
YYYY-MM-DD-title.md
```

提交并推送后，GitHub Pages 会自动重新构建站点。
