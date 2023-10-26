# Tai
👻 在 Windows 上统计 `软件` 使用时长和 `网站` 浏览时长

<img src="index.jpg" width=600 />

## 开始使用

#### 环境

使用之前，你的电脑可能需要安装 [.NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework) `4.8` 或更高的版本（一般Win10以上的系统不需要安装）。如果在启动 Tai 时没反应，请点击左侧链接下载安装。

#### 使用

1. 在 [releases](https://github.com/Planshit/Tai/releases) 中可以下载已经编译好的 exe 可执行文件压缩包。建议优选选择标记有 `Latest` 的版本，划到下方的 `Assets` 找到 `Taix.x.x.x.zip` 点击下载；
2. 下载压缩包后解压到合适的位置（建议不要解压到桌面、系统盘），进入解压后的文件夹内，找到 `👻Tai.exe` ，启动程序，成功启动后你将在状态栏看到 👻 图标；
3. 使用 `网站浏览统计` 功能需要安装相应的浏览器拓展并且在 设置 > 常规 > 功能中启用。[下载安装浏览器插件说明](https://github.com/Planshit/Tai/discussions/279);
4. 请以管理员身份运行 Tai ，否则无法统计部分软件。

#### 卸载

1. 在设置中停用开机自启动（如果启用了）；
2. 删除所有文件即可完成卸载。

#### 基本操作

鼠标双击图标进入程序主界面，右击显示菜单。

## 了解更多

#### 为什么使用 Tai？

帮助你了解自己把时间花在了什么地方，从而更好地做一些计划。或者，为了每周回顾自己的摸鱼成果。~~工作只是换取薪酬，摸鱼才是赚钱。~~

#### 应用白名单

支持仅统计白名单内的软件，在设置 > 行为中可以启用此功能。

#### 关联进程

如果你希望在多屏工作时将其他屏幕所使用的软件同时记录使用时长，可以在设置中将相应的软件进程添加到一个关联列表中。添加完成后，只要使用了关联列表的其中一个软件，就会同步更新使用时长到列表里的其他软件上，但前提是其他软件需要正处于运行中（即使在后台或者没有焦点都行）。一个软件只能关联一次，不能重复与其他软件关联。

#### 过滤应用和网站

可以在设置 > 行为中通过进程名称/URL或者正则表达式对不需要统计的软件/网站进行过滤。

#### 数据储存和导出

Tai 使用不加密 `SQLite` 数据库将统计数据存储在本地 `运行目录\Data\data.db` 中。可以在设置中将统计的数据以 `.xlsx` 和 `.csv` 两种文件格式导出。

#### 睡眠监测

Tai 能够一定程度地发现用户离开电脑从而停止统计，也可以在设置 > 行为中停用此功能以实现不间断统计。

#### 联网和隐私

除了检查更新/升级软件时（需要主动在设置中检查更新）之外完全没有其他网络请求。Tai 并不会收集和上传你的任何信息。

##  ❤️ + 👻

开源软件的更新动力来源于用户的支持，无论是精神还是经济上，如果 Tai 给你带去了帮助请给开发者一些鼓励把~

#### 来杯☕

<img src="https://github.com/noberumotto/noberumotto/raw/master/wechat.jpg" width="256px"/> <img src="https://github.com/noberumotto/noberumotto/raw/master/alipay.jpg" width="256px" />

[关于&联系 →](https://github.com/noberumotto/noberumotto/blob/master/about.md)
