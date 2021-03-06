---
title: 弹窗解决方法
weight: 1030
layout: single
---

常见弹窗问题解答
--------------------------------
以下图文列举了一些常见的FiveM弹窗以及报错解决方案，请自行对号入座进行解决

### 报错：`adhesive.dll+7D394`

![adhesive.dll+7D394](/fivemba/1-1.png)

- 将您的操作系统更新至最新版本

### 报错：`Exception unhandled！`

![Exception unhandled！](/fivemba/1-2.png)

- GTAV 目录路径或 FiveM 目录路径含有中文，路径内的中文改为英文即可

### 报错：`FiveM does not support running under elevated privileges`

![1-3](/fivemba/1-3.png)

- 不要用管理员运行 FiveM

### 弹窗：`FiveM is already installed.`

![1-4](/fivemba/1-4.png)

- FiveM 自动安装到了用户文件夹内，可以在开始菜单直接启动 FiveM。C:\Users\*\*

### 弹窗：`Select the folder containing Grand Theft Auto V`

![1-5](/fivemba/1-5.png)

- 这个弹窗的意思是要让你选择你的 GTAV 根目录。
  选择 Grand Theft Auto V 目录即可解决。

### 报错：`Could not find the game executable`

![1-6](/fivemba/1-6.png)

- 出现这个窗口可以尝试下再多启动几次试试，有的玩家一个电脑上有可能会有很多版本的 GTAV，前往 FiveM.app 文件夹，打开 CitizenFX.ini 将里面的路径改为自己的游戏路径即可。

### 报错：`picface64.dll+11422D`

![1-7](/fivemba/1-7.png)

- 使用 ENG 输入法即可解决

想要在 FiveM 服务器聊天框中输入中文，建议使用搜狗输入法。其他均会闪退。

### 弹窗：`You are currently using an outdated version of Windows.`

![1-8](/fivemba/1-8.png)

- 点确定即可，弹窗内容是建议将您的系统更新至 Win10 1703 版本或以上。能启动 FiveM，就不用管。

### 报错：`ros-patches-five.dll+F86B0`

![1-9](/fivemba/1-9.png)

- 出现 ROS 字样，多半可以判断为是杀软后台杀掉了 FiveM 某个进程，关掉杀软，启动 FiveM，如果 FiveM 文件被杀软杀掉，建议去下 FiveM 包，到时如果出现损坏解压即为重装。

### 报错：`Could not load component gta-core-five.dll - Windows error code 126.`

![1-10](/fivemba/1-10.png)

- 出现 DX 字样或者 Windows error code 等错误去百度将常用的游戏运行库装一遍(倒数第二页)。再下载一个 DX 修复工具增强版即可。

### 报错：`deleting old https://***********.xz failed (err=5)`

![2-1](/fivemba/2-1.png)

- 使用任务管理器，结束后台所有的 FiveM 进程，再重启 FiveM。如果不行就尝试重启电脑，再启动 FiveM。(一直出现一直循环这个操作)

### 弹窗：`FiveM needs to update the game cache`

![2-2](/fivemba/2-2.png)

- 有的玩家一个电脑上有可能会有很多版本的 GTAV，而 FiveM 自动选择的 GTAV 版本过低导致的该弹窗，前往 FiveM Application Data(又称 FiveM.app)，打开 CitizenFX.ini 将里面的路径改为最高版本的游戏路径即可。还有种情况就是你的游戏版本不够导致的，目前 FiveM 要求同步正版版本。详情去看教程第十页。

### 报错：`GTA5+129FC20`

![2-3](/fivemba/2-3.png)

- 只要出现 GTA5+ 随机符号 都属于常规的闪退，重进服务器即可。如果是服务器内某一个特定地点出现特定弹窗，那么请联系服务器服主解决。目前无法根治这个弹窗。

### 乱码：游戏服务器内出现口口口这样的乱码

<!-- ![2-4](/fivemba/2-4.png) -->

- 进入繁体/简体服务器出现口口乱码字样解决方法：去工具包内解压出简/繁文件即可
  首先，确保你的 FiveM 内的语言是你的系统语言。举个栗子：你的系统是简体字系统，那么你的 FiveM-设置-显示-语言就一定要是简体中文。反之亦然。
  然后看工具包内的简/繁文件。当你要进繁体服务器的时候，将 FiveM 关掉，用管理员运行修改繁体文件.bat 即可。 然后当你要进简体服务器的时候，将 FiveM 关掉，用管理员运行修改简体文件.bat 即可。

### 报错：`Could not sign on to the social club`

![2-5](/fivemba/2-5.png)

- 一般是 R\*账号错误导致的该弹窗

### 报错：`Moving of https://*********** failed (err=32)`

![2-6](/fivemba/2-6.png)

- 使用任务管理器，结束后台所有的 FiveM 进程，再重启 FiveM。如果不行就尝试重启电脑，再启动 FiveM。

### 卡在：`正在加载...`

![2-7](/fivemba/2-7.png)

- 尝试 LSP 或 DNS 修复一遍，一般玩家都不会出现该弹窗，或者很快就消失。如果长时间卡在这个地方，尝试按第网络问题解决。

### 闪退：`进入主界面后突然闪退`

![2-8](/fivemba/2-8.png)

- 显示 FiveM 主界面后，突然闪退，或者鼠标卡主等情况，同属于网络问题，主要是因为 FiveM 有众多国家的服务器，会全部加载，网络有问题的玩家就会直接闪退。按教程第四页网络问题解决即可。

### 报错：`连接服务器时报错`

<!-- ![2-9](/fivemba/2-9.png) -->

以下情况在 Connect 连接服务器时出现

|  提示                                        |      说明                 |
|----------------------------------------------|---------------------------|
|Couldn' connect to server                     |无法连接到服务器            |
|Timed out after 60 seconds                    |网络超时                   |
|Connect failed                                |连接失败                   |
|Failure when receiving data form the peer     |从服务端接收数据时失败      |
|Connection was reset                          |链接被服务端重置            |
|等情况                                                                    |

一般是延迟过高或者服务器关闭，重启引起，服务器内有大量玩家就是自己的问题了，第一时间去服务器群组了解服务器最新状态即可。外服延迟问题只有 SSTap 配合优质节点或者其他工具即可解决。或者一直点链接也有几率解决。

### 报错：`OneSync is not whitelisted,have to wait a little while longer,maybe set sv_lan`

`OneSync(policy type onesync_plus) is not whitelisted for this server,or requesting whitelist status failed.`

`have to wait a little while longer `

`No FiveM ticket was specified. If this is an offline server,maybe set sv_lan?`

出现该内容是 FiveM 的问题，尝试删除 FiveM.app 文件夹内的 cache.xml 文件，重启 FiveM，多链接，一直连接服务器，一般可以解决。还有种原因是因为 FiveM 的服务器列表有中转效果，不少玩家因为这个中转出现上面这种情况，尝试用 Direct Connect 直连解决即可。

### 报错：`FiveM needs to update the game cache`

![3-1](/fivemba/3-1.png)

- 出现这个弹窗说明你的游戏版本不够。教程第一页有说明，要使用最新的游戏文件才可以，FiveM 吧联机交流群内有下载工具（正版分流），可以满速下载且跟 steam 版本一样。
  还有一种可能就是你的电脑上有多个版本的 GTA5，而 FiveM 自动将路径定位至低版本的 GTA5。解决方法：打开 FiveM.app 文件夹，找到 CitizenFX.ini 文件，将里面路径修改为自己最高版本 GTA5 路径即可。

### 游戏内：`掉地图，掉虚空，地图加载不出来`
以上三种情况可以汇总为几个解决方法。首先还是先判断问题。 
1. 固定位置掉地图，掉虚空，这种多见于游戏文件损坏等情况，一般检测下游戏文件 md5(可以与朋友的 md5 比对一下)或者 steam 验证游戏文件完整性即可。当然也可以直接重下 GTA5。
2. 随机位置掉地图，掉虚空，出现这种问题，很多情况都是因为客户端与服务端之间的链接不稳定导致的，跟延迟也有关，随机位置，一般情况都是在服务器游玩过程中，地图加载不出来，然后掉出地图，这种问题一般可以按网络问题解决，当然也可以换个服务器看看有没有这种情况。
3. 第三种就是属于服务端插件导致的了，因为服务端插件众多，这种情况不好确定，目前我见过的也只有车店看车，或者同步插件导致的地图加载不出来，如果是这种情况引起的地图加载不出来，尝试联系相关服务器服主解决。
4. 还有一种情况就是玩家看玩家瞬移，这个是正常现象，因为对方延迟过高。实际上他是在开车，而另一个玩家看他却是上下瞬移的情况。一般情况下让对方重上一下服务器，或者上车下车，加载同步出来就好。

### 报错：`kernelbase.dll+2A1C8`

![3-3](/fivemba/3-3.png)

- 尝试将显卡驱动更新试试，然后关掉所有关于 GPU 超频的软件，驱动自带的超频请恢复默认设置。
  如果是窗口模式闪退请切换全屏，如若是全屏闪退，请切换至窗口。
  或者使用 DDU 驱动卸载工具，卸载显卡驱动，然后安装低版本的显卡驱动。

教程第三页可以看到，也可以去官网下载，版本更新很快。地址：https://www.wagnardsoft.com/

### 报错：`d3d11.dll+17510D`

![3-4](/fivemba/3-4.png)

- 出现上面这个弹窗说明是你的系统文件导致的 FiveM 闪退，一般多为网上那种 Ghost，精简版，强化版，优化版系统，这种系统一般删减过系统文件，或者改过其他地方，尝试按教程内的 12 页也就是下一页解决即可。 或者尝试下把系统内的 DirectX 修复下，或者重装一遍系统驱动。

### 报错：`d3d11.dll+*******`

![3-5](/fivemba/3-5.png)

- 出现 D3d11.dll + 随机号码 等问题，原因是在你修改了游戏文件导致的，FiveM 要求游戏文件不能有任何修改。解决方法，请尝试使用 steam 验证游戏文件即可。
  其他渠道下载的玩家，请自行重新下载或找其他玩家发你一份无修改的文件。或删掉游戏文件内的 d3d11.dll 文件或 d3d10.dll 文件

### 报错：`A component of your computer is preventing you from being able to play FiveM`

![3-6](/fivemba/3-6.png)

官方给出的解决方法与解释：

首先，您不会被禁止使用 Windows /系统。因此，您不会被禁止，因为取消禁止“实际上意味着禁止作弊者。您与作弊者具有冲突的标识符应该是唯一的如果禁止标识的后缀不均（例如 13），则可能由于以下原因而被禁止：

1. 您作弊，但试图绕开禁令
2. 您使用网吧玩游戏-使用另一台 PC
3. 您使用 Geforce Now 玩（或共享 PC 的另一种云游戏服务）-不要玩 不支持 Geforce Nowit
4. 您的 Windows ID 不唯一，PCmanufacturer（例如 Cyberpowerpc 和 Picha）格式的重新安装 Windows 安装不佳，或者与您的制造商联系
5. 您具有不唯一的 MAC 地址，常见的是 BIOS 很少闪烁（例如 Intel 适配器） ）或草图制造商重复使用 MAC 地址（例如 Huawei 4Gadapters）-使用其他适配器或重置 MAC 地址（对于 Intel 适配器）

☆ 为机翻 ☆

大概意思我解释下。之前也有这种情况的发生，有使用 Windows 设置 重置系统解决的，也有重置自己系统所有驱动解决的。意思就是你的系统有不止一个 mac 地址，一般来说一个网卡一个地址，你系统上却有不止一个，所以才会导致这个弹窗，解决方法先按上面两个解决试试，如果你有更好的解决方法，欢迎来 FiveM 交流群提供，到时会写上解决方法提供玩家署名。

### 报错：`FiveM needs to update the game cache`

![3-7](/fivemba/3-7.png)

- 提示这个意思是你要去下载 FiveM 更多文件，上面写着大约有 1083.80MB，过程中需要网络连接，点是即可。

如果下载过程中出现 download of 等弹窗，请前往教程第四页解决即可。

如果你的网络不是很好建议去 FiveM 吧置顶帖联机中下载完整的 FiveM 包，如果后续出了问题，解压出来就等于重装，非常方便。

### 报错：`Authentication error`

![3-8](/fivemba/3-8.png)

- 你输入的 R\*账号内没有 GTAV 正版才会出现这个弹窗。可以在 FiveM 吧交流群内找 1911 要个另类教程，按上面操作即可。


## 系统问题解决篇

### 报错：`DXGI 1.2 support is required to run FiveM`

![3-9-1](/fivemba/3-9-1.png)

![3-9-2](/fivemba/3-9-2.png)

![3-9-3](/fivemba/3-9-3.png)

第一个弹窗出现后一般会弹出一个网页，是微软更新系统的网页，下载相应更新，安装即可。倘若安装之后，打开 FiveM 还是闪退，则代表您的操作系统是 GHOST 系统，或者是某种精简版，优化版，强化版操作系统，这种系统一般都删除过相应的更新文件，系统内必备组件，只能重装操作系统。FiveM 吧交流群 群文件内有重装系统工具，当然您也可以自己重装系统，建议您前往 MSDN 或者微软官网下载原版 Windows 10 操作系统。其他地方，如系统之家等等，都是修改过的系统不建议使用。在一般情况下，我测试了所有 Windows 7 操作系统，只要是原版 Windows 7 操作系统，在更新至最新的情况下，使用 FiveM 没有任何问题。

工具包已放入 MSDN 系统重装工具，该工具是从微软直接下载安装，可以保证系统的源头可查，原版系统没有任何问题。

PS：如果你的系统盘是 C 盘，千万不要把 MSDN 下载的系统镜像放入 C 盘，否则安装系统格式化会导致无法安装系统。


### 报错：`FiveM has stopped working`

![3-10](/fivemba/3-10.png)

Windows10 操作系统出现该弹窗有两种可能，一种是你在 FiveM 服务器中玩着玩着突然闪退导致的，这种情况可以直接重进服务器。另一种，就是你第一次启动 FiveM，导致 FiveM 闪退，解决方法只有重装 Windows 10 原版操作系统。

笔记本卡 800X600 或彩色小屏幕不动
--------------------------
  先试试这一步系统设置，详细图文教程请[点击查看][gpu]。

1. 打开 Windows 设置-系统-显示-选择图形设置
2. 选择要设置首选项的框中，选择经典应用
3. 然后选择 FiveM 目录-FiveM.exe
4. 单击选项
5. 选择高性能

### 用于 NVIDIA GPUs

1. 打开 NVIDIA 控制面板
2. 转到 3D 设置 3D 首选项
3. 把 FiveM.exe 添加进去，然后选择 高性能 NVIDIA 处理器

### 用于 AMD RADEON GPU

1. 右键桌面，打开 AMD RADEON 设置
2. 选择游戏 添加 FiveM.exe

### AMD Catalyst GPU

1. 右键单击桌面的任何部分，然后选择“Catalyst Control Center”。
2. 转到左侧的“电源”选项卡。
3. 选择“可切换应用程序图形设置” 
4. 在此下方，您将看到“添加应用程序”
5. 选择 FiveM.exe
6. 选择 高性能

### Intel® 图形 GPU

1. 右键打开 图形属性
2. 选择高级模式，打开 3D 选项卡
3. 3D 首选项 设置为性能 点击应用


如果还是无效果，请将系统电源选项改为最高性能。

大概意思就是将你的(系统)(显卡驱动)（电源）都设置为高性能，其中系统和显卡驱动都要讲 FiveM.exe 添加进去并设置高性能。还要记得，将集显驱动，与独显驱动，都要设置好高性能。

出现一种特殊情况，有的笔记本电脑，可以将电源调整至平衡状态也可以解决。但是独显，核显驱动与系统设置都要设置高性能。


进服务器卡加载解决
--------------------------

### 判断方法

- F8 出现 Triggering LoadGameFirstLaunch()

- F8 加载资源不动或者出现 ERROR 字样

- F8 显示 GetLocationInfoFromIP 等字样
  ![4-2-1](/fivemba/4-2-1.png)

- 进入服务器一直在下载服务器索引文件，长时间不加载其他内容

- 链接服务器过程中，一直卡在 download ****

- ding XXXX 等插件且数据不动

- F8 出现以下字样
  ![4-2](/fivemba/4-2.png)

### 卡加载解决办法：

#### 情况一
是网络问题，比如特定服务器可以进，而其他服务器无法进入，可以按上面网络问题解决。

#### 情况二
ERROR 和无法加载相应文件可以先打开 GTA5 线上和线下都一样挂在后台（只要 GTA5 程序在后台就可以）然后使用 FiveM 进入相应服务器，就不会出现加载错误等情况。ERROR 也有可能是网络问题。首先要先判断服务器内是否有玩家，如果没玩家，就去服务器相应群聊群组，了解服务器最新在线情况。如果服务器内有玩家，多半是自己问题。
	问题解决方法提供者：慕夏星乐斯(百度贴吧)

#### 情况三(测试)
将 FiveM 文件夹放到与 GTA5 同一个盘内(一个盘符下就可以，不用放到 GTA5 文件夹内然后给 FiveM 创建快捷方式放到桌面即可)

#### 情况四
1. 出现卡加载情况，通过教程第三页 清除验证工具
2. 然后重新验证进入服务器。 （鸿哥提供解决方法）

删 FiveM 服务器缓存方法：打开 FiveM 文件目录，找到 `cache` 文件夹将该文件夹内除 game 以外的所有文件夹删除即可。

_（删除缓存后进入服务器需要重新下载资源，谨记）_


[gpu]: https://forum.fivem.net.cn/t/topic/35