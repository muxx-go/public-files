# 序闻 SIGNAL · AI 资讯

黑白编辑刊物风格的 AI 资讯网站，包含 7 条经官方原文核对的资讯。

- 网站源码：[`ai-news/index.html`](ai-news/index.html)
- 内容核验日期：2026-09-20
- 当前为静态精选，尚未接入自动采集。
- 本地预览：下载 HTML 后直接使用浏览器打开。

## GitHub Pages

仓库 Settings → Pages → Build and deployment → Source 选择 **GitHub Actions**。
随后在 Actions 中运行 **Deploy AI news to GitHub Pages**（Run workflow）。以后修改 ai-news 目录会自动发布。

部署成功后访问：https://muxx-go.github.io/public-files/

工作流只发布 ai-news 目录，不会将仓库中其他文件打包到网页。
