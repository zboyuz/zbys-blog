# Zepher 的个人网站

一个无需安装依赖的静态个人网站。主页、文章页、响应式样式和交互脚本都在 `dist/` 下，可直接部署到任何静态托管服务。

## 本地预览

在项目根目录运行 `node preview.mjs`，然后访问 `http://127.0.0.1:8000`。

## 修改内容

- 主页文字和链接：`dist/index.html`
- 第一篇文章：`dist/writing/hello.html`
- 视觉样式：`dist/assets/paper.css`
- 移动菜单和页脚年份：`dist/assets/app.js`

部署配置位于 `.openai/hosting.json`。网站当前通过 Sites 发布；`dist/` 也兼容 GitHub Pages 等静态托管。
