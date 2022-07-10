# 使用 Hiper-Vlan 功能与好友一起游玩 Minecraft （我的世界）Java 版

**本教程分 简单版 和 命令行版。**

本教程的 Minecraft （我的世界）为 Java版本的客户端，并非服务端（及客户端为用户使用的Java版本，你日常使用的）

注意，由于 Github 在国内访问速度慢，请稍等片刻……

## 简单版（Windows 平台使用）

简单版用到了作者：[梦游泪世](https://mcer.cn/circle-people?id=6) 的 hiper启动程序

可在上方链接中找到本程序的更新日志

[点击此处下载](https://mcer.cn/circle/491.html)

下载并解压，运行程序，即可看到如下窗口：

↓以下是 创建方 和 加入方 各自要操作的东西↓

<iframe src="//player.bilibili.com/player.html?aid=258369837&bvid=BV1sa411Q7Ar&cid=768847377&page=1" allowfullscreen="allowfullscreen" width="100%" height="500" scrolling="no" frameborder="0"></iframe>

### 创建方操作视角

[首先点击此处下载程序](https://mcer.cn/circle/491.html)

第一次使用输入 `1` ，安装虚拟网卡，成功后就不用再输入了

![](https://gitcode.net/chearlai/ff/-/raw/main/10.png)

#### 然后输入 `3` 回车即可启动，其中 `Set interface IP Address:`和`\7`之间的IP就是用来使加入 Hiper 的用户，例如图中的是 `6.2.94.183` ，下面会用到他！

![](https://gitcode.net/chearlai/ff/-/raw/main/18.png)

————————————————————

**须知（如果看不懂，可以慢慢看或跳过暂时这一步骤，稍后再看）：**

键入 `3` 为非凭证加入，属于免费版，免费版会在启动后**随机**分配可用的IP（如一次启动时1.1.10.1，那么下次启动该就是1.2.1.1，每次随机分配），

以及在运行后 30 分钟断连，此时 Hiper启动程序会自动重启 HIPer（创建方断连，需要将重新将IP重新发送给加入方，让他加入这个 IP）

或者使用凭证，使用凭证不会有上述问题，免费版的用户也可以访问你（创建方因使用凭证启动，创建方的 HIper IP是不变的）

#### 使用凭证：

输入 `2` 回车，粘贴凭证密钥回车，即可带凭证启动 Vlan

**注意：使用了一次凭证后（无论失败与否），会有 10 分钟的冻结期，冻结期内使用凭证暂时无法使用，只有过了冻结期才可以使用**

————————————————————

然后将 Hiper 程序放一边就行了

然后使用任意启动器启动 Minecraft （我的世界） Java版

![](https://gitcode.net/chearlai/ff/-/raw/main/19.png)

然后进入你的单人存档，按键盘上的 `Esc退出键` 打开游戏菜单，

点击 `对局域网开放`，此时你的聊天栏中会出现 `本地诺戏已在端口 XXXX 上开启` 这个 XXXX 就是游戏开放的端口，

操作视频：

![](https://gitcode.net/chearlai/ff/-/raw/main/20.gif)

#### 只需要将 [Hiper 给你分配的 IP](#输入-3-回车即可启动-vlan-功能其中-set-interface-ip-address-7之间的ip就是用来使加入-hiper-的用户例如图中的是-6294183) 和 游戏开放端口 组合成 IP:XXXX （如下方组合），

并发送给你的加入方，至此创建方的工作就告一段落了！

操作视频：

![](https://gitcode.net/chearlai/ff/-/raw/main/22.gif)

### 加入方视角

[首先点击此处下载程序](https://mcer.cn/circle/491.html)

第一次使用输入 1 ，安装虚拟网卡，成功后就不用再输入了

![](https://gitcode.net/chearlai/ff/-/raw/main/10.png)

————————————————————

**须知（如果看不懂，可以慢慢看或跳过暂时这一步骤，稍后再看）：**

键入 `3` 为非凭证加入，属于免费版，免费版会在启动后**随机**分配可用的IP（如一次启动时1.1.10.1，那么下次启动该就是1.2.1.1，每次随机分配），

以及在运行后 30 分钟断连，此时 Hiper启动程序会自动重启 HIPer（创建方断连，需要将重新将IP重新发送给加入方，加入方断连则需重新进入创建方所发给你的 IP）

或者使用凭证，使用凭证不会有上述问题，免费版的用户也可以访问你（加入方断连只需重新加入创建方提供的IP）

#### 使用凭证：

输入 `2` 回车，粘贴凭证密钥回车，即可带凭证启动 Vlan

**注意：使用了一次凭证后（无论失败与否），会有 10 分钟的冻结期，冻结期内使用凭证暂时无法使用，只有过了冻结期才可以使用**

————————————————————

然后将 Hiper 放一边就行了

使用任意启动器启动 Minecraft （我的世界） Java版

点击 `多人游戏` > `直接连接`

将[创建方发给你的IP](#只需要将-hiper-给你分配的-ip输入-3-回车即可启动-vlan-功能其中-set-interface-ip-address-7之间的ip就是用来使加入-hiper-的用户例如图中的是-6294183-和-游戏开放端口-组合成-ipxxxx-如下方组合) 输入并加入

（若加入出现问题，请逐个查看[常见问题](#一些常见问题)）

至此，你已经成功的使用 简单版 的方式使用了 Hiper-Vlan 功能与好友一起游玩 Minecraft （我的世界）了！

![](https://gitcode.net/chearlai/ff/-/raw/main/26.gif)

## 命令行版（非 Windows 平台使用）

[施工中……]()

## 一些常见问题

### 游戏的版本，模组双方都要一致吗？

需要！

### 加入方突然在游戏里退出，加入方游戏里进服进不了怎么办？

**请检查创建方和加入方的Hiper是否有断连**

**如果还是不行，双方请重新启动 Hiper**

- 使用简单版

创建方断连：只需将IP重新发给他，加入方用这个IP加入房间

加入方断连：只需重新进入房间即可

- 使用命令行版

施工中……

以下是可能游戏给出的提示信息：

以“无效会话”开头的中文提示:你的登录方式有误，请查阅下方关于[登录方式](#联机对正版离线等登录方式有要求吗)的条目。

![](/p/26.png)

上图如果你在游玩时出现，则创建方关闭了他的游戏

连接超时:加入方或者创建方的网络环境不佳或延迟过高。

### Hiper 的 Vlan 功能可以用于其他游戏的联机吗?

联机功能本质上提供了对外开放的端口，因此可以用于其他联机方式相似的游戏。

### 联机对正版、离线等登录方式有要求吗？

如果使用“对局域网开放“的方式联机，房主可以使用任意登录方式，加入者必须使用

账户或外置登录账户启动游戏，不能使用离线登录！否则在加入服务器时会提示无效会话。这是MC本身的限制。

如果在登录方式上遇到了问题，可以尝试:

1、让加入方使用非离线账户，及正版账户或者外置登录账户

2、让让创建方安装 [自定义局域网联机(Lan Server Properties， 1.12-最新)](https://www.mcmod.cn/class/2754.html) 或 [简单联机(Server.Properties for LAN， 1.7.2-1.12.2)](https://www.mcmod.cn/class/1158.html)模组（加入者无需安装）

![](https://gitcode.net/chearlai/ff/-/raw/main/23.png)

按照如下图或视频的操作方法关闭正版认证：

自定义局域网联机 Lan Server Properties：

![](https://gitcode.net/chearlai/ff/-/raw/main/24.png)

简单联机 Server.Properties for LAN：

*(true为开启，false为关闭，在视频中我输入错了)*

<video width="888" height="540" controls>
  <source src="https://gitcode.net/chearlai/ff/-/raw/main/25.mp4"  type="video/mp4">
  您的浏览器不支持 HTML5 video 标签。请更新你的浏览器！
</video>



