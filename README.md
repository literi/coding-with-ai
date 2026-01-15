# coding-with-ai

## 本地开发

```bash
bundle install
bundle exec jekyll serve
```

## 主题说明

- 自定义 wiki 风格主题：顶部导航 + 左侧目录（jekyll-toc）。
- 样式入口：`assets/css/main.scss` → `_sass/main.scss`。
- 布局：`_layouts/default.html`（主框架）、`_layouts/home.html`（首页）。
- 头部/脚注：`_includes/header.html`、`_includes/footer.html`。

## 配置

- 站点与导航在 `_config.yml` 里配置。
- TOC 插件 `jekyll-toc`，通过 `{% toc %}` 在侧边栏渲染目录。
Learn How to coding with ai
