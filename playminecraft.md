# 使用 Hiper-Vlan 功能与好友一起游玩 Minecraft （我的世界）Java 版

支持短链接：[http://8r5.cn/V7ZGd](http://8r5.cn/V7ZGd)

## 小声逼逼

本文章并不是很完美，可能会因为更新换代而更不上更新脚步，所以希望看到这的同学，若发现了问题，欢迎在 Github 上提交 [Issues](https://github.com/zkitefly/hiper-d/issues) 和 [Pull requests](https://github.com/zkitefly/hiper-d/pulls)

**本教程分 简单版 和 命令行版。**

本教程的 Minecraft （我的世界）为 Java版本的客户端，并非服务端（及客户端为用户使用的Java版本，你日常使用的）

注意，由于 Github 在国内访问速度慢，请稍等片刻……

## 简单版（Windows 平台使用）

简单版用到了作者：[梦游泪世](https://mcer.cn/circle-people?id=6) 的 hiper启动程序

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/33.png)

可在上方链接中找到本程序的更新日志

[点击此处下载](https://mcer.cn/circle/491.html)

下载并解压，运行程序，即可看到如下窗口：

<iframe src="//player.bilibili.com/player.html?aid=258369837&bvid=BV1sa411Q7Ar&cid=768847377&page=1" allowfullscreen="allowfullscreen" width="100%" height="500" scrolling="no" frameborder="0"></iframe>

**↓以下是 创建方 和 加入方 各自要操作的东西↓**

### 创建方操作视角

*注：如果你是非 Windows 平台的用户，[请跳转至此](/命令行版.md#创建方操作视角)；是 Windows 平台的用户请继续往下看↓*

[首先点击此处下载程序](https://mcer.cn/circle/491.html)

第一次使用输入 `1` 并回车，安装虚拟网卡，成功后就不用再输入了

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/32.png)

#### 然后输入 `3` 回车即可启动，其中 `Set interface IP Address:`和`\7`之间的IP就是用来使加入 Hiper 的用户，例如图中的是 `6.2.94.183` ，下面会用到他

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/18.png)

<details>
<summary>须知（如果看不懂，可以慢慢看或跳过暂时这一步骤，稍后再看）：</summary>
<pre><code>
键入 3 为非凭证加入，属于免费版，免费版会在运行后 30 分钟断连，此时 Hiper启动程序会自动重启 HIPer

或者使用凭证，使用凭证不会有上述问题，免费版的用户也可以访问你

#### 使用凭证

输入 2 回车，粘贴凭证密钥回车，即可带凭证启动 Vlan

注意：使用了一次凭证后（无论失败与否），会有 10 分钟的冻结期，冻结期内使用凭证暂时无法使用，只有过了冻结期才可以使用
</code></pre>
</details>

然后将 Hiper 程序放一边就行了

然后使用任意启动器启动 Minecraft （我的世界） Java版

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/19.png)

然后进入你的单人存档，按键盘上的 `Esc退出键` 打开游戏菜单，

点击 `对局域网开放`，此时你的聊天栏中会出现 `本地诺戏已在端口 XXXX 上开启` 这个 XXXX 就是游戏开放的端口，

操作视频：

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/20.gif)

#### 只需要将 [Hiper 给你分配的 IP](#然后输入-3-回车即可启动其中-set-interface-ip-address和7之间的ip就是用来使加入-hiper-的用户例如图中的是-6294183-下面会用到他) 和 游戏开放端口 组合成 IP:XXXX

**并发送给你的加入方**，至此创建方的工作就告一段落了！

操作视频：

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/22.gif)

### 加入方视角操作视角

*注：如果你是非 Windows 平台的用户，[请跳转至此](/命令行版.md#加入方操作视角)；是 Windows 平台的用户请继续往下看↓*

[首先点击此处下载程序](https://mcer.cn/circle/491.html)

第一次使用输入 1 ，安装虚拟网卡，成功后就不用再输入了

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/33.png)

<details>
<summary>须知（如果看不懂，可以慢慢看或跳过暂时这一步骤，稍后再看）：</summary>
<pre><code>

键入 3 为非凭证加入，属于免费版，免费版会在运行后 30 分钟断连，此时 Hiper启动程序会自动重启 HIPer

或者使用凭证，使用凭证不会有上述问题，免费版的用户也可以访问你

#### 使用凭证

输入 2 回车，粘贴凭证密钥回车，即可带凭证启动 Vlan

注意：使用了一次凭证后（无论失败与否），会有 10 分钟的冻结期，冻结期内使用凭证暂时无法使用，只有过了冻结期才可以使用
</code></pre>
</details>

然后将 Hiper 放一边就行了

使用任意启动器启动 Minecraft （我的世界） Java版

点击 `多人游戏` > `直接连接`

将[创建方发给你的IP](#%E5%8F%AA%E9%9C%80%E8%A6%81%E5%B0%86-hiper-%E7%BB%99%E4%BD%A0%E5%88%86%E9%85%8D%E7%9A%84-ip-%E5%92%8C-%E6%B8%B8%E6%88%8F%E5%BC%80%E6%94%BE%E7%AB%AF%E5%8F%A3-%E7%BB%84%E5%90%88%E6%88%90-ipxxxx-) 输入并加入

（若加入出现问题，请逐个查看[常见问题](#一些常见问题)）

至此，你已经成功的使用 简单版 的方式使用了 Hiper-Vlan 功能与好友一起游玩 Minecraft （我的世界）了！

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/26.gif)

## 命令行版（非 Windows 平台使用）

[跳转](/命令行版.md)

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

创建方断连：需要重新[键入命令](/命令行版.md#%E8%BE%93%E5%85%A5%E5%B9%B6%E8%BF%90%E8%A1%8C%E4%BB%A5%E4%B8%8B%E5%91%BD%E4%BB%A4%E5%90%AF%E5%8A%A8-hiper) `sudo ./hiper v` 启动Hiper，并将IP重新发给他，加入方用这个IP加入房间

加入方断连：需要重新[键入命令](/命令行版.md#%E8%BE%93%E5%85%A5%E5%B9%B6%E8%BF%90%E8%A1%8C%E4%BB%A5%E4%B8%8B%E5%91%BD%E4%BB%A4%E5%90%AF%E5%8A%A8-hiper-1) `sudo ./hiper v` 启动Hiper，然后重新进入房间即可

以下是可能游戏给出的提示信息：

以“无效会话”开头的中文提示:你的登录方式有误，请查阅下方关于[登录方式](#联机对正版离线等登录方式有要求吗)的条目。

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/26.png)

↑上图如果你在游玩时出现，则创建方中途关闭了游戏↑

![](/p/34.png)

↑上图如果加入方加入时出现，此问题是由于游戏在校验账户时出错↑

↑你可能使用的是离线账户，请使用非离线账户，[相关问题想点击此跳转](#%E8%81%94%E6%9C%BA%E5%AF%B9%E6%AD%A3%E7%89%88%E7%A6%BB%E7%BA%BF%E7%AD%89%E7%99%BB%E5%BD%95%E6%96%B9%E5%BC%8F%E6%9C%89%E8%A6%81%E6%B1%82%E5%90%97)

↑若使用的是正版账户，请重新启动游戏，若多次尝试任然提示此，请重新在启动器内登录正版账户↑

连接超时:加入方或者创建方的网络环境不佳或延迟过高。

### Hiper 的 Vlan 功能可以用于其他游戏的联机吗?

联机功能本质上提供了对外开放的端口，因此可以用于其他联机方式相似的游戏。

### 联机对正版、离线等登录方式有要求吗？

房主可以使用任意登录方式，加入者必须使用

**正版账户或**[**外置登录账户**（点此处查看详情）](https://bing.com/search?q=%E3%80%8A%E5%90%AF%E5%8A%A8%E5%99%A8%E3%80%8B%E5%A4%96%E7%BD%AE%E7%99%BB%E5%BD%95%E8%B4%A6%E6%88%B7%E9%85%8D%E7%BD%AE)**启动游戏，不能使用离线登录！**否则在加入服务器时会提示无效会话。这是MC本身的限制。

如果加入方在登录方式上遇到了问题，可以尝试:

1、让加入方使用非离线账户，及正版账户或者[外置登录账户](https://bing.com/search?q=%E3%80%8A%E5%90%AF%E5%8A%A8%E5%99%A8%E3%80%8B%E5%A4%96%E7%BD%AE%E7%99%BB%E5%BD%95%E8%B4%A6%E6%88%B7%E9%85%8D%E7%BD%AE)

2、让让创建方安装 [自定义局域网联机(Lan Server Properties， 1.12-最新)](https://www.mcmod.cn/class/2754.html) 或 [简单联机(Server.Properties for LAN， 1.7.2-1.12.2)](https://www.mcmod.cn/class/1158.html)模组（加入者无需安装）

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/23.png)

按照如下图或视频的操作方法关闭正版认证：

自定义局域网联机 Lan Server Properties：

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/24.png)

简单联机 Server.Properties for LAN：

*(true为开启，false为关闭，在视频中我输入错了QAQ)*

<video width="888" height="540" controls>
  <source src="https://zkitefly.github.io/hiper-d/p/25.mp4"  type="video/mp4">
  您的浏览器不支持 HTML5 video 标签。请更新你的浏览器！
</video>
