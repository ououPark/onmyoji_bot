# 欢迎

[![GitHub release](https://img.shields.io/github/release/academicdog/onmyoji_bot)](https://github.com/AcademicDog/onmyoji_bot/releases) ![GitHub top language](https://img.shields.io/github/languages/top/academicdog/onmyoji_bot) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/academicdog/onmyoji_bot) ![GitHub repo size](https://img.shields.io/github/repo-size/academicdog/onmyoji_bot) ![GitHub](https://img.shields.io/github/license/academicdog/onmyoji_bot)
![platforms](https://img.shields.io/badge/platform-win32|win64-brightgreen.svg) [![GitHub issues](https://img.shields.io/github/issues/academicdog/onmyoji_bot.svg)](https://github.com/academicdog/onmyoji_bot/issues) [![GitHub closed issues](https://img.shields.io/github/issues-closed/academicdog/onmyoji_bot.svg)](https://github.com/academicdog/onmyoji_bot/issues?q=is:issue+is:closed) ![GitHub commit activity](https://img.shields.io/github/commit-activity/m/academicdog/onmyoji_bot) ![GitHub contributors](https://img.shields.io/github/contributors/academicdog/onmyoji_bot.svg)

如果您对本[项目](https://github.com/AcademicDog/onmyoji_bot)感兴趣，欢迎加入[我们](https://github.com/AcademicDog/onmyoji_bot/graphs/contributors)！

* * *

# 主要功能
本工具用于阴阳师代肝，为各位阴阳师大佬养老护肝所用。
<img align="right" width="220" src="https://raw.githubusercontent.com/AcademicDog/myresource/master/usage.png" alt="copy URL to clipboard" />

### 特性

- 御魂
  - 单人御魂
  - 作为司机组队御魂，自动邀请
  - 作为乘客组队御魂，自动接受邀请
  - 双开御魂
- 业原火
  - 自动刷贪、嗔、痴卷
- 御灵
  - 自动刷御灵
- 探索
  - 完成探索，识别经验怪，支持自动换狗粮
- 其他
  - 在战斗过程中，该脚本会自动拒绝所有悬赏封印的邀请。
  - 如果60s程序没有任何操作（卡机、体力空等），视为体力用光，为了保护加成，自动关闭YYS。
  - 该脚本仅使用了画面找色，鼠标后台点击的函数，完全模拟人类玩家行为，没有使用任何内存读写函数。在敏感位置添加了均匀分布的随机时间漂移，和随机坐标漂移。**但仍然可能存在使用风险**。

### 使用环境

> 阴阳师PC版客户端，默认分辨率(1136x640)
>
> Windows 10和Windows 7，屏幕(1920x1080)，显示设置100%
>
> 如需运行源码，需要Python3 32位

* * *

# 使用方法

### 单人刷御魂/业原火/御灵

1.  打开本工具，切换至御魂选项卡；

1.  游戏中进入御魂/业原火/御灵主界面（就是有“挑战”按钮的页面），请提前备好式神并**锁定阵容**；

1.  点击本工具的“开始”按钮。

### 组队刷御魂

1.  打开本工具，切换至御魂选项卡，根据自身情况选择“单人司机”或者“单人乘客”；

1.  游戏中进入组队页面，请提前备好式神并**锁定阵容**，司机请在**探索**页面开车，这样能减少1秒左右延迟；

1.  点击本工具的“开始”按钮。

### 单人探索

1.  打开本工具，切换至探索选项卡；

1.  在游戏种提前将狗粮队长放在阴阳师最左边，并且**取消锁定阵容**；

1.  游戏中点开需要探索的章节（就是有“探索”按钮的页面）；

1.  点击本工具的“开始”按钮。

* * *

# 注意事项

1.  窗口现在可以完全后台，可以被遮挡，但是**不能最小化**。

1.  不要开启游戏中的“模型描边”。

1.  当使用 Windows 7 系统时，需要调整系统的画面设置：把主题调为最丑最挫的那个。在 Windows 10 系统中，不需要调整系统画面设置。

1.  当使用高分辨率屏幕时，在阴阳师客户端程序兼容性选项里，不要勾选“替代高DPI缩放行为”，这个选项应该是默认不勾选的。

1.  如果不想安装运行环境，可以访问下载最新已[编译](https://github.com/AcademicDog/onmyoji_bot/releases)版本，该版本有图形界面，同时注意.exe文件和/img文件夹应该放在同一目录后再运行。

1.  探索换狗粮的时候，默认是换上第一个N卡，因此注意**不要**对N卡点击“喜欢”，导致反复换上一个满级的狗粮。

1.  如果下载缓慢，可以访问[网盘](https://pan.baidu.com/s/1jhHrjRGWmu9yOLq9ryApJA)下载，提取码：gyj9

* * *

# 更新日志

更新日志请点击[这里](https://github.com/AcademicDog/onmyoji_bot/blob/master/CHANGELOG.md)

### 下一步工作计划

暂无

* * *

# 特别感谢
特别感谢society765在本项目中给与的启发，本项目在其[工作基础](https://github.com/society765/yys-auto-yuhun)上修改完成。

同时感谢sup817ch的图像识别思路，本项目game_ctl模块基于其[工作基础](https://github.com/sup817ch/AutoOnmyoji)。

感谢每一个在[ISSUE](https://github.com/AcademicDog/onmyoji_bot/issues)中提出问题的人。