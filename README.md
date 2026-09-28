# 钧天 · Juntian

钧天让你在电脑上使用 AI 助理处理文件、分析数据和完成项目，并在 Android 手机上继续会话、补充资料与确认操作。

这是钧天的安装包发布仓库，用于发布 macOS（Apple Silicon）和 Android 测试版、更新说明与 SHA-256 校验值。

- 下载入口：[gasmeter.cloud](https://gasmeter.cloud/)
- 所有版本：[GitHub Releases](https://github.com/MelorTang/juntian-releases/releases)

## 安装

Mac：下载 ZIP 并完整解压，运行其中的「安装钧天.command」，同时安装 App 与 Runtime；无需 Node 或 pnpm。请保留整个解压目录，不要单独拖出 App。

Android：下载 APK 后使用系统安装器安装，不需要 Expo Go。更新前保留已有资料；遇到签名冲突时不要直接卸载旧应用。

当前版本为测试版：Mac 尚未经过 Apple 公证，Android 使用测试签名。Windows、Intel Mac 和 iOS 暂无安装包。

## 跨设备连接

桌面设置 → 移动设备，填写 `wss://gasmeter.cloud/relay`，保存并启用，再生成配对码。手机扫码后核对两端验证码。

当前任务由电脑执行，需要电脑联网、钧天运行且不休眠。模型服务由使用者自行配置；安装包不含账号、API Key、会话或设备配对凭证。

第三方组件许可随安装包提供。各版本的验证范围与已知限制见对应 Release 说明。
