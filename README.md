# Signal 翻译母包下载指引

这是独立的 Signal 翻译母包下载项目，和 WhatsApp、通讯翻译中枢分开。

## 下载

- 最新版本：1.0.3
- 下载地址：https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.0.3/yitaifang-signal-translator-mother-v1.0.3.zip

## 使用流程

1. 下载 zip 后解压到一个固定文件夹，例如 D:\Signal翻译工具\Signal翻译母包。
2. 运行 SignalTranslatorMother.exe 或 Signal翻译母包.exe。
3. 第一次使用时填写自己的 OpenAI Key，模型默认选择 gpt-4.1-mini 即可。
4. 点击“保存配置”。
5. 点击“新建 Signal 翻译版”，母包会在当前母包目录下创建一个新的独立 Signal 副本。
6. 如果桌面没有快捷方式，运行 Create-Desktop-Shortcut.cmd。中文入口 创建桌面快捷方式.cmd 也会转到同一个脚本。

## 更新说明

- 修复非中文系统/不同代码页下快捷方式脚本乱码的问题。
- 母包会单独检查本仓库的 ersion.json。
- 新版 Signal 副本启动时也会自动检查更新并显示进度条。
- 不会影响原版 Signal、WhatsApp 或通讯翻译中枢。