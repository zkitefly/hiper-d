# Hiper

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/1.png)

## 提示

**本文章的某些内容过时，正在更新！**

- 本文章由 Zkitefly 制作，若要搬运，请在 [Discussions](https://github.com/zkitefly/hiper-d/discussions) 反馈并获得授权！

- 若对本文章有任何问题或疑惑，可以在以下联系方式找到我

  - [GitHub Discussions](https://github.com/zkitefly/hiper-d/discussions)

  - mcer.cn QQ群:
    - •ᴗ• 这里 · ① · mcer.cn
       群号：235256586
    - •ᴗ• 这里 · ② · mcer.cn
       群号：212927890
    - •ᴗ• 这里 · ③ · mcer.cn
       群号：93365639

## Hiper 介绍

不知道怎么说(

## Hiper 准备工作

以下列举的是 Windows 平台的准备工作，非 Windows 平台请[访问此](/Hiper准备工作.md)

下载两个文件：

*一个是必须下载:*

[windows-tap](https://gitcode.net/chearlai/f/-/raw/master/d/tap-windows-9.21.2.exe)

该程序为安装 Hiper 安装所需的虚拟网卡

请勿在安装时修改 Destination Folder，即安装目标文件夹！

请放心安装，本程序仅266 KB (272,409字节)

如果你安装过了，请勿再次安装！

若想卸载，请运行该卸载程序：C:\Program Files\TAP-Windows\Uninstall.exe

*一个是 Hiper 本体（按照你的计算机架构下载，**不知道下哪个就下载 hiper-windows-amd64.exe**）：*

[hiper-windows-amd64.exe（Windows 平台 X86_64位 ☆一般选择此下载☆）](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-amd64.exe)

[hiper-windows-i386.exe（Windows 平台 X86_32位）](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-i386.exe)

[hiper-windows-arm64.exe（Windows 平台 AArch64（Arm64））](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-arm64.exe)

**注意！下载完 Hiper 本体，请重命名为 `hiper`，接下来的教程程序名都会是他**

*小技巧：打开 Hiper 所在目录，并在文件资源管理器的导航栏中点击一下空白处显示输入框，然后输入 `cmd` 并回车，即可在 Hiper 所在目录打开 CMD。*

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/12.gif)

## Hiper 功能介绍

Hiper 一共分为两大功能：

Vlan 功能和 Chat 功能

可用命令：
   
   chat 通过覆盖网络聊天
   
   vlan 加入建立在覆盖网络上的虚拟专用网络.
   
   completion 为指定的shell生成自动完成脚本（本文不做赘述，想了解可加入[QQ群](#提示)）
   
   help 关于任何命令的帮助（本文不做赘述）

### Vlan 功能介绍

Vlan 功能可以加入建立在覆盖网络上的虚拟专用网络，**该功能直白的说是通过将计算机的网络通过虚拟网卡加入至 Hiper 网络中，使其加入 Hiper 的其他用户可通过 Hiper 分配的 IP 互相访问计算机网络。**此功能可以用在游戏联机（Minecraft）、分享文件甚至是你计算机下的创建的网站。

[使用 Hiper Vlan 功能与好友进行 Minecraft 联机](/playminecraft.md)

### Vlan 使用

输入命令使用 Vlan 功能：

```
hiper v

hiper lan

hiper vlan
```

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/13.png)

你可以在上述命令添加额外参数，如：

```
hiper v -h
```

<details>
<summary>Vlan 调节参数介绍（一般用户请忽略）</summary>
<pre><code>
      --community string 要加入的社区 ID（默认为“公共”）
      
      --dev string 给 TAP（虚拟网卡）设备的名称（即 hiper0）（默认是自动生成的；仅在 Linux、macOS 和 Windows 平台下支持）
      
      --force-relay 强制使用中继服务器（默认会自动判断是否使用中继）
      
      -h, --help  Vlan的帮助
      
      --ice 字符串 逗号分隔的 STUN 服务器和中继服务器列表（默认 [stun:stun.the.bb:3478,stun:stun.l.google.com:19302,username:password@turn:120.92.140.174 :3478,wfchat:wfchat@turn:wildfirechat.cn:3478,openrelayproject:openrelayproject@turns:openrelay.metered.ca:443?transport=tcp])
      
      --ips 字符串 以逗号分隔的 IP 网络列表，用于从 TUN 设备声明 IP 地址并提供给 TUN 设备（在 Windows 平台下，仅支持一个 IPv4 和一个 IPv6 地址；在 macOS 平台下，忽略 IPv4 地址）（默认 [6.0 .0.0/7])
      
      --key string 社区的加密密钥（默认为“null”）
      
      --mac 字符串 MAC 地址，提供给 TAP（虚拟网卡）设备（即 3a:f8:de:7b:ef:52）（默认是自动生成的；仅在 Linux 平台下支持）
      
      --parallel int 用于解码帧的线程数（默认 4）
      
      --password string 社区密码（默认为“null”）
      
      --signal-addr string 信令地址（默认“wss://signaling.mcer.cn/”）
      
      --static 尝试静态声明在 --ips 标志中指定的确切 IP，而不是从指定网络中随机选择一个
      
      --timeout duration 等待连接的时间（默认 10 秒）
      
      -t, --token string 用户认证密钥（通过 https://mcer.cn/shop 或在QQ群（在 # 提示 中有提到）里询问获取 token）
</code></pre>
</details>

**须知：**

直接使用 Vlan 功能，默认是公共渠道，公共渠道会在运行后 30 分钟断连，

断连后 CMD/终端 中会显示如图信息，此时你可以键入命令重新加入，

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/11.png)

或者使用凭证，使用凭证不会有断连问题，且默认启动的用户也可以访问你

使用凭证命令：
```
hiper v -t "<凭证>" 
```
`<凭证>` 替换成你获取到的凭证密钥即可

凭证可在 [https://mcer.cn/shop](https://mcer.cn/shop) 或 [加入QQ群](#提示) 获取

**注意！非 Windows 平台需要 Root 权限，及输入以下命令调用 `sudo` 获取权限：**

```
sudo hiper v
```

### Chat 功能介绍

在 Hiper 网络上聊天。他就像是我们的微信群，默认是加入我们的公共网络，也就是公共群，大家可以在此发送文本内容。

### Chat 使用

输入命令使用 Chat 功能
```
hiper chat --names <名称>
hiper cht --names <名称>
hiper c --names <名称>
```
其中 `<名称>` 替换成想取的名称即可

当 CMD/终端 出现 `HI <名称>` 时，代表可以正常发送消息了

![](/p/35.png)

你可以发送任意文本内容

当也是用 Chat 功能的用户就可以看到 TA 人发来的文本内容

要是在加入的同时，也有人在使用 Chat，则会显示在使用人的名称。如图：

![](/p/36.png)

*注意，Chat 功能不需要调用虚拟网卡，也不需要管理员权限（sudo），无凭证参数*

你可以在上述命令基础上添加额外参数，如：
```
hiper c -h
```

<details>
<summary>Chat 调节参数介绍（一般用户请忽略）</summary>
<pre><code>
      --channel string 用于协商名称的频道（默认为“hiper/chat/id”）

      --channels 字符串 以逗号分隔的社区中要加入的频道列表（默认 [hiper/chat/primary]）

      --community string 要加入的社区 ID（默认为“public”）

      --force-relay 强制使用中继服务器

      -h, --help 聊天帮助

      --ice 字符串 逗号分隔的 STUN 服务器和中继服务器列表（默认[stun:stun.the.bb:3478,stun:stun.l.google.com:19302,openrelayproject:openrelayproject@turns:openrelay.metered.ca:443?transport=tcp])
      
      --key string 社区的加密密钥（默认为“null”）

      --kicks duration 等待踢的时间（默认 5 秒）

      --names 字符串 逗号分隔的名称列表，尝试从中声明一个

      --password string 社区密码（默认为“null”）

      --signal-addr string 信令地址（默认“wss://signaling.mcer.cn/”）

      --timeout duration 等待连接的时间（默认 10 秒）
</code></pre>
</details>

## 第三方可视化 Hiper 操作

这些第三方让 Hiper 的操作更为简便，或者将 Hiper 的功能新手可使用他来初步了解。

#### hiper启动程序（仅 Windows 平台下使用）

作者：[梦游泪世](https://mcer.cn/circle-people?id=6)

可在上方链接中找到本程序的更新日志

[点击此处下载](https://mcer.cn/circle/491.html)

下载并解压，运行程序，即可看到如下窗口：

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/9.png)

第一次使用需要输入 `1` 回车，安装虚拟网卡

然后你就可以使用该程序的功能了

输入 `3` 回车，使用 Hiper 的 [Vlan](#vlan-功能介绍) 功能

输入 `2` 回车，调用凭证使用 Hiper [Vlan](#vlan-功能介绍) 功能

输入 `4` 回车，使用 Hiper 的 [Chat](#chat-功能介绍) 功能 

其他的功能直接看启动菜单就行了


