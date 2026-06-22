# Signal 翻译中枢下载指引

这是独立的 Signal 翻译中枢下载项目，和 WhatsApp、通讯翻译中枢分开。

## 下载

- 最新版本：1.1.10
- 下载地址：https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.1.10/yitaifang-signal-translator-mother-v1.1.10.zip

## 使用流程

1. 下载 zip 后解压到一个固定文件夹，例如 D:\Signal翻译工具\Signal翻译中枢。
2. 运行 `Signal翻译中枢.exe`。
3. 第一次使用时填写自己的 OpenAI Key，模型默认选择 `gpt-4.1-mini` 即可。
4. 点击“保存配置”。
5. 点击“新建 Signal 翻译版”，中枢会在当前目录下创建新的独立 Signal 副本。
6. 如果是旧版，直接运行“一键安装或覆盖.cmd”，会自动查找桌面入口并覆盖程序文件，不删除账号数据。

## 更新说明

- 中枢会检查本仓库的 `version.json`。
- 本版本使用完整包更新，避免旧补丁包造成循环更新。
- 更新/覆盖会保留 `Signal翻译账号` 和 `mother-config.json`。
- 不会影响原版 Signal、WhatsApp 或通讯翻译中枢。