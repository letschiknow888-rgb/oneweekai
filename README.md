# Cross-Border AI Assistant · GitHub Pages 版

这是一个**零构建**的单文件 Demo，适合直接托管在 GitHub Pages 上预览。

## 快速开始（推荐 /docs 目录）
1. 新建 GitHub 仓库，将本项目中的 `docs/index.html` 上传到你的仓库 `docs/` 目录。
2. 打开仓库 **Settings → Pages**：
   - **Source** 选择 *Deploy from a branch*
   - **Branch** 选择 `main`（或你的默认分支）
   - **Folder** 选择 `/docs`
3. 保存，等待 1–2 分钟，页面将显示公开访问地址。

## 使用说明
- 左侧填写品牌、产品、关键参数、语气与语言；可模拟输入 ASIN 进行示例填充
- 点击「一键生成」→ 右侧展示 *Listing / 关键词 / 广告文案* 三个标签页的结果
- 支持点击复制、复制全部关键词

> 该 Demo 仅用于 UI/交互演示。接入真实数据源/大模型 API 后，即可升级为生产版本。

## 自定义
- 你可以直接修改 `docs/index.html` 内文案/字段/样式（使用 Tailwind CDN）。
- 如需改造成 React/Vite/Next 等工程化项目，我可以提供完整骨架与自动部署脚本。
