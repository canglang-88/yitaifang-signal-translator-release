# Signal 翻译中枢下载指引

这是独立的 Signal 翻译中枢下载项目，和 WhatsApp、通讯翻译中枢分开。

## 推荐下载：小引导安装包

- 最新版本：1.1.10
- 小引导包：https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.1.10/yitaifang-signal-translator-bootstrap-v1.1.10.zip

小引导包很小，适合发给别人。它会自动读取云端最新版，显示下载进度，下载完整包后自动覆盖安装，避免直接下载大包几分钟超时后像卡死。

## 备用：完整包下载

- 完整包：https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.1.10/yitaifang-signal-translator-mother-v1.1.10.zip

## 使用流程

1. 优先下载小引导包并解压。
2. 双击 `Signal翻译中枢-在线安装.cmd`。
3. 等待进度显示完成，程序会自动覆盖/安装并启动。
4. 第一次使用时填写自己的 OpenAI Key，模型默认选择 `gpt-4.1-mini` 即可。
5. 点击“新建 Signal 翻译版”，中枢会在当前目录下创建新的独立 Signal 副本。

## 旧版覆盖更新

- 如果电脑上已有旧版，在线安装会从桌面快捷方式寻找旧版位置并覆盖程序文件。
- 覆盖时会保留 `Signal翻译账号` 和 `mother-config.json`。
- 不会删除已有副本、登录数据、聊天记录和本机配置。

## 更新说明

- 中枢会检查本仓库的 `version.json`。
- 本版本云端索引不使用旧补丁包，避免循环更新。
- 不会影响原版 Signal、WhatsApp 或通讯翻译中枢。