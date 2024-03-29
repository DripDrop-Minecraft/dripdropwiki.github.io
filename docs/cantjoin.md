## 搜索指向关键词
> - 无法加入
> - 搜索不到
> - 进不来、进不去、进不了

## 常见情形及解决方法

## ① 未知的主机+无法刷新出motd
#### 问题描述
在多人游戏界面无法刷出正确的motd信息，且在加入服务器后显示“未知的主机”。

![无法刷出motd](pics/nomotd.png)
![未知的主机](pics/unknown%20host.png)
#### 解决方案
**A 检查IP是否正确，尝试用以下两个IP连接**

+ 主域名：`dripdrop.games`
+ 备用域名： `dripdrop.wiki`

请参照上面给出的域名，检查输入的服务器地址是否存在、正确。尤其是检查有没有使用**全角字符**（比如中文冒号`：`，类似`ＡＢＣ１２３`这类间距特别大的字母和数字）输入，然后尝试再登录几次。

**B 尝试重启客户端**

俗话说重启能解决99%的问题，可以尝试重启客户端后再次连入。

**C 尝试重启电脑**

俗话说重启能解决99%的问题，重启客户端不行的话，试试重启电脑。


**D 检查电脑网络，是否正常访问网页或连接其他服务器**

如果网络正常，但依然无法连接，可能是由于DNS未刷新。

可以在键盘上同时按`WINDOWS`+ `R`，打开“运行”对话窗，输入`cmd`命令，点击“确认”按钮。

在打开的命令行窗口中，输入`ipconfig/flushdns`命令，键盘上按 `Enter`回车键即可刷新。

**E 更换启动器**

如果玩家使用了特定版本的PCL2启动器，可能会出现无法正常搜索和连接大部分**基于面板服**运营的服务器的问题，建议更换PCL2版本，或使用HMCL或者官方启动器。

## ② 登录失败 : 无效会话(请尝试重启游戏及启动器) 
#### 问题描述
能刷新出外面的motd，但加入服务器后显示“无效会话”。

![有motd界面](pics/havemotd.png)
![无效会话](pics/nomojanglogin.png)
#### 解决方案
**A 确认自己是否正版登录**

服务器有正版验证，需要正版登录后才能加入。

**B 尝试重启客户端**

俗话说重启能解决99%的问题，可以尝试重启客户端后再次连入。

**C 尝试重启电脑**

俗话说重启能解决99%的问题，重启客户端不行的话，试试重启电脑。

**D 检查自己电脑是否能连上mojang的验证服务器**

可以在键盘上同时按`WINDOWS`+ `R`，打开“运行”对话窗，输入`cmd`命令，点击“确认”按钮。

在打开的命令行窗口中，输入`ping authserver.mojang.com`命令，键盘上按 `Enter`回车键。

能够正常连接的话是“丢失 = 0 (0% 丢失)”，如图

![正常ping通mojang验证服务器](pics/canping.png)

如果是“丢失 = 4 (100% 丢失)”，则可以尝试[修改host](https://www.bilibili.com/read/cv15851058/)。

**E 更新自己的网卡驱动**
> [!warning] 
> 请先尝试上述几个解决方案，此方案只出现过一次，仅供参考！某玩家无法正常连接到XBOX进行正版验证，后通过更新网卡驱动解决。

## ③ 身份验证异常

#### 问题描述

提示“身份验证失败”、“身份验证服务器宕机”或“身份验证服务器维护中”。表明玩家/本服主机与Mojang的验证服务器连接有异常。

#### 解决方案

**A 等待几秒后尝试重新连接**

如果玩家/本服主机发生网络波动，或是有官方公告证实Mojang验证服务器发生故障，可以尝试该方案。

可以等待4秒左右后重新尝试进入(注意不要连续加入)

**B 使用加速器VPN等科学上网工具**

如果有可靠的消息来源证实Mojang验证服务受到中国国家防火墙（GFW）干扰，那么只能使用科学上网手段进入游戏了。

## ④ Out Of Memory客户端崩溃

#### 问题描述

客户端提示“Out Of Memory”（内存溢出），这种情况通常是玩家没有给游戏分配足够的内存。

#### 解决方案

**A 配置足够内存**

在<font color=red>64</font>位电脑，你为启动器分配的最大内存应该至少达到<font color=red>2 GB</font> 或 <font color=red>2048 MB</font>。

**B 重启电脑**

关闭其他应用并重启电脑，在游玩时，尽量少打开其他应用占用内存。

**C 换电脑**

如果你的电脑是亲戚朋友淘汰下来或者垃圾堆里淘来的32位老古董，建议趁早花钱享受64位的新世界。

## ⑤ Internal Exception: java.net.SocketException: Connection reset

#### 问题描述

客户端提示“Internal Exception: java.net.SocketException: Connection reset”（连接重置），这种情况通常是网络连接出问题，也可能是正版验证服务器无法连接上。

#### 解决方案

**A 等待几秒后重新尝试连接**

等待大约4-5秒后，重新尝试进入服务器。

**B 在群内寻求帮助**

目前玩家都能通过多次尝试进入服务器，如果你一直无法进入服务器的话可以加群询问。
