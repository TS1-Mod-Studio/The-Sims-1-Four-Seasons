# 模拟人生 四季

**首个公开测试版 · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · **简体中文** · [繁體中文](README.zh-TW.md)

让 The Sims Legacy Collection 里的社区也有四季。暴风雨来临时，模拟市民会跑进屋里；到了冬天，花园会覆上一层积雪。再次读档时，地段的天气和日历会接着上次的进度继续。这是一款由玩家制作的非官方模组。

![笼罩在雾中的住宅地段](../media/weather.png)

[秋天的树叶](../media/autumn.png) · [积雪覆盖的花园](../media/winter.png) · [完整图集（ZIP，8 张图片）](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## 地段里的四季

- 随着季节更替，地段会出现降雨、雷暴、冰雹、降雪、暴风雪和雾。想自己选择天气时，可以放置气象站，还能选用魔法雨或魔法雾。
- 秋天树叶会变色。冬天的积雪会盖住道路、植物和墓碑等户外物品。孩子们可以在水坑里踩水玩，积雪够厚时，模拟市民还能堆雪人。
- 模拟市民、猫和狗都会被雨淋湿，也会跑去避雨。雨有时能浇灭户外的火。天气面板可以分别调节这些效果。游戏加载时会播放模组的原创主题曲《Pocztówka z doliny》。

## 下载与安装

需要在 64 位 Windows 上安装完整版 The Sims Legacy Collection（游戏版本 **1.10.0** 或 **1.10.7**）和 [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0)。请预留几 GB 的磁盘空间，另留足够空间备份游戏存档。

1. 在 GitHub 的 [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) 页面打开 **1.0.0-beta.1**，从 **Assets** 区域下载 `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip`。
2. 先保存游戏，再退出游戏和天气程序。把整个 ZIP 解压到新文件夹，让 `data` 文件夹和 `Setup.exe` 位于同一目录。
3. 运行 `Setup.exe`，选择包含 `sims.exe` 的游戏文件夹。先点击 **检查兼容性** 检查文件，再点击 **安装**。安装程序会校验并备份文件，然后给电脑上已有的游戏资源打补丁。如果某个必需文件与预期不符，安装会停止。
4. 等待安装完成提示。以后请通过桌面上的 **The Sims Cztery Pory Roku** 快捷方式，或天气程序安装目录中的 `Launch-weather.cmd` 启动游戏。天气服务和读档时恢复天气的功能会一起启动。

请用安装程序修补游戏文件。程序会在每次修补前后校验文件的哈希值，`sims.exe` 保持原样。可选物品只有在本机已装有受支持的版本时才会被修补。

## 在游戏中使用

进入地段后，天气会自动变化。按 `Ctrl+Alt+R` 打开面板，可以调节降水、音效、日历和天气对模拟市民的影响。物品菜单和面板默认采用游戏语言。在面板中手动选择其他语言后，下次启动时生效。

## 备份、更新与卸载

安装程序会备份需要修改的文件、游戏存档和天气数据。请将 `backups` 文件夹与 `install-state.json` 文件一起保存在 `%LOCALAPPDATA%\TS1CzteryPoryRoku` 下的程序安装目录中。部分地段天气数据存放在 `%LOCALAPPDATA%\TS1RainOverlay`。要手动恢复存档，请先退出游戏。请保留游戏和天气程序原来的安装位置。

存档备份包含 Windows“保存的游戏”文件夹中的 `Electronic Arts\The Sims 25`，以及游戏目录中已有的 `UserData`, `UserData2` 等文件夹。每次备份都会建立单独的文件夹。`save-backup.json` 记录了原始路径和校验值，方便你在手动恢复存档时找到对应的文件。

更新时先退出游戏和天气程序，将新 ZIP 解压到另一文件夹，再在安装程序中选回原来的游戏目录。要卸载模组，请关闭两者，打开之前保留的 `Setup.exe`，选择 **选项 → 卸载**。卸载会还原原来的游戏文件，并保留存档和备份。如果以后还想使用模组里的物品，请先备份地段，再移除模组继续游戏。

如果安装意外中断，请选择 **选项 → 撤销更改**。如果还原时提示有文件已被修改，请保留完整报错信息和备份。如果 Windows 拒绝写入，请用同一个 Windows 账户以管理员身份运行 `Setup.exe`。

## 测试进度和问题反馈

安装程序已针对上述两个游戏版本进行检查。其他电脑、较低配置硬件和全部 17 种语言的完整游戏流程仍在测试中。若开启 NVIDIA 游戏内覆盖后天气显示卡顿，可以关闭该覆盖功能再试一次。

请在 GitHub 的 [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) 提交游戏版本、模组版本、语言及复现步骤。遇到画面问题时，请附上截图，并注明当时的天气、缩放级别、镜头方向、楼层和墙壁显示模式。安装问题请提供完整的报错信息。公开日志前请检查其中是否包含带有个人信息的文件路径。
