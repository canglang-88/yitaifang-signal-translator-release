# Signal 翻译中枢下载指引

这是独立的 Signal 翻译中枢下载项目，和 WhatsApp、通讯翻译中枢分开。

## 推荐下载：小引导安装包

- 最新版本：1.1.21
- 推荐下载：[yitaifang-signal-translator-bootstrap-v1.1.21.zip](https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.1.21/yitaifang-signal-translator-bootstrap-v1.1.21.zip)

小引导包只有几 KB，适合发给别人。它会自动读取云端最新版，显示下载进度，下载完整包后校验文件并覆盖安装，避免直接下载大包时长时间无反馈、看起来像卡死。

## 备用：完整包下载

- 完整包：[yitaifang-signal-translator-mother-v1.1.21.zip](https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.1.21/yitaifang-signal-translator-mother-v1.1.21.zip)

只有小引导包被安全软件拦截或网络环境无法自动下载时，才建议手动下载完整包。

## 使用流程

1. 优先下载小引导包并解压。
2. 双击 `一键安装或覆盖.cmd`。
3. 等待进度显示完成，程序会自动覆盖/安装并启动。
4. 第一次使用时填写自己的 OpenAI Key，模型默认选择 `gpt-4.1-mini` 即可。
5. 点击“新建 Signal 翻译版”，中枢会在当前目录下创建新的独立 Signal 副本。

## 旧版覆盖更新

- 如果电脑上已有旧版，在线安装会从桌面快捷方式寻找旧版位置并覆盖程序文件。
- 覆盖时会保留 `Signal翻译账号`、`mother-config.json`、OpenAI 配置、登录数据、聊天记录和本机设置。
- 不会影响原版 Signal、WhatsApp 或通讯翻译中枢。

## 更新说明

- 中枢会检查本仓库的 `version.json`。
- v1.1.21 新增可移动的翻译开关，可以临时关闭自动翻译后直接发送中文。
- 本版本不使用旧补丁包，避免循环更新。
