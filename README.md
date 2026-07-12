# Signal 翻译中枢下载指引

这是独立的 Signal 翻译中枢下载项目，和 WhatsApp、通讯翻译中枢分开。

## 推荐下载：小引导安装包

- 最新版本：1.1.20
- 推荐下载：[yitaifang-signal-translator-bootstrap-v1.1.20.zip](https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.1.20/yitaifang-signal-translator-bootstrap-v1.1.20.zip)

小引导包只有几 KB，适合发给用户。它会自动读取云端最新版，显示下载进度，下载完整包后校验 SHA256，再覆盖安装。

## 备用：完整包下载

- 完整包：[yitaifang-signal-translator-mother-v1.1.20.zip](https://github.com/canglang-88/yitaifang-signal-translator-release/releases/download/v1.1.20/yitaifang-signal-translator-mother-v1.1.20.zip)

只有小引导包被安全软件拦截，或当前网络无法自动下载时，才建议手动下载完整包。

## 使用流程

1. 优先下载小引导包并解压。
2. 双击 `一键安装或覆盖.cmd`。
3. 等待进度显示完成，程序会自动覆盖/安装并启动。
4. 第一次使用时填写自己的 OpenAI Key，模型默认选择 `gpt-4.1-mini` 即可。
5. 点击“新建 Signal 翻译版”，中枢会创建新的独立 Signal 翻译副本。

## 旧版覆盖更新

- 如果电脑上已有旧版，安装脚本会从桌面快捷方式寻找旧版位置并覆盖程序文件。
- 覆盖时会保留 `Signal翻译账号`、`mother-config.json`、OpenAI 配置、登录数据、聊天记录和本机设置。
- 不会影响原版 Signal、WhatsApp 或通讯翻译中枢。

## v1.1.20 重点

- 中枢保留授权、云端禁用、云端到期和“重新检测”入口。
- 子程序保持稳定翻译入口：`YitaifangSignalTranslator.exe` 184KB。
- 子程序保持稳定翻译核心：`YitaifangSignalTranslator.dll` 269KB。
- 不把 `SignalLicenseGate.exe` 或 153MB 门禁壳放进翻译入口。
- 新建副本和“更新全部副本”都从稳定 `Template` 同步。
- 完整包不包含 OpenAI API Key、Signal 登录数据、聊天记录、翻译缓存或本机备份。
