# Signal 翻译母包下载指引

这是独立的 Signal 翻译母包下载项目，和 WhatsApp、通讯翻译中枢分开。

## 下载

- 最新版本：1.0.2
- 下载地址：https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.0.2/yitaifang-signal-translator-mother-v1.0.2.zip

## 使用流程

1. 下载 zip 后解压到一个固定文件夹，例如 D:\Signal翻译工具\Signal翻译母包。
2. 运行 Signal翻译母包.exe。
3. 第一次使用时填写自己的 OpenAI Key，模型默认选择 gpt-4.1-mini 即可。
4. 点击“保存配置”。
5. 点击“新建 Signal 翻译版”，母包会在当前母包目录下创建一个新的独立 Signal 副本。
6. 如果桌面没有快捷方式，运行包内的 创建桌面快捷方式.cmd。

## 更新说明

- 母包会单独检查本仓库的 ersion.json。
- 新版 Signal 副本启动时也会自动检查更新。
- 如果发现新版，会显示下载进度条；下载完成后只更新当前副本程序并重启。
- 更新不会删除已经创建的 Signal翻译账号 登录数据。
- 不会影响原版 Signal、WhatsApp 或通讯翻译中枢。