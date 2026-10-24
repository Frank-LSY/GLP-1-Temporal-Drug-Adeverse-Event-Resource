# GLP-1 Evidence Atlas — GitHub Pages 静态网页包

这是最新版连续滚动交互式研究网页，无需构建、Node.js、后端或 API 密钥。

## 部署到 GitHub Pages

1. 解压 ZIP，将里面的文件和 assets 文件夹上传到 GitHub 仓库根目录。请确保 index.html 位于根目录，而不是再套一层文件夹；不要只上传 ZIP 本身。
2. 打开仓库 Settings → Pages。
3. 在 Build and deployment 中将 Source 设为 Deploy from a branch。
4. 选择 main 分支、/(root) 文件夹，然后保存。
5. 部署完成后，在同一页面点击 Visit site。

包内包含空白 .nojekyll 文件。所有 CSS、JavaScript 和图片均使用相对路径，可部署到 GitHub Pages 项目子路径，不需要修改仓库名称或域名。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 文件

- index.html：网页结构与文字内容
- style.css：桌面与移动端样式
- app.js：信号、映射、时间线、图表、模型示例等交互
- data.js：页面使用的研究数值与原始内容
- assets/：原文图表和队列图
- .nojekyll：静态部署标记

## 本地查看

解压后直接用现代浏览器打开 index.html，即可查看网页和交互。图表、样式、脚本与原图均包含在包内；仅外部论文链接需要网络。

## 内容说明

保留全部作者、单位和 Accepted at the 2026 AMIA Annual Symposium 标识。
研究数值来自所提供的文章和 slides；治疗间隔沙盒及模型计算器明确标为教学示例。此包不包含患者级数据。
