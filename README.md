# Cookmoji 私有作品「发布后分享」Demo

本仓库仅演示 Quick PRD 已确认的方案 A：本人未发布的私有作品在分享前先明确告知公开影响；用户确认后，依次完成发布到广场和复制邀请码。

## 交互范围

- 私有作品分享入口显示「发布后分享」。
- 点击后展示公开影响确认弹窗。
- 取消时不发布、不复制邀请码。
- 确认后显示「正在发布…」，处理期间防止重复操作。
- 发布成功并取得有效邀请码后，提示「已发布到广场，邀请码已复制」。
- 已发布作品不在本 Demo 的改造范围内，继续沿用现有「复制邀请码」流程。

## 相关资料

- [Quick PRD](https://groupultra.sg.larksuite.com/docx/FW5adGItZodYhvxbOqvlEjGpgEb)
- [Cookmoji iOS 正式代码库](https://github.com/groupultra/stickit-ios-swift)

本仓库是交互原型，不是可直接合入 iOS 工程的 Swift 生产代码。研发实现时应复用正式工程现有的发布状态与发布动作。

## 本地预览

直接打开 `index.html`，或使用任意静态文件服务器运行仓库根目录。
