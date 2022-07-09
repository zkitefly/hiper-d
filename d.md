# Hiper

![](https://gitcode.net/chearlai/ff/-/raw/main/1.png)

## 提示

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



## Hiper 准备工作

以下列举的是 Windows 平台的准备工作，非 Windows 平台请[访问此](/Hiper准备工作.md)

下载两个文件：

*必须下载:*

[windows-tap](https://gitcode.net/chearlai/f/-/raw/master/d/tap-windows-9.21.2.exe)

该程序为安装 Hiper 安装所需的虚拟网卡

请勿在安装时修改 Destination Folder，即安装目标文件夹！

请放心安装，本程序仅266 KB (272,409字节)

如果你安装过了，请勿再次安装！

若想卸载，请运行该卸载程序：C:\Program Files\TAP-Windows\Uninstall.exe

*Hiper 本体（按照你的计算机架构下载，**不知道下哪个就下载 hiper-windows-amd64.exe**）：*

[hiper-windows-amd64.exe（Windows 平台 X86_64位 ☆一般选择此下载☆）](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-amd64.exe)

[hiper-windows-i386.exe（Windows 平台 X86_32位）](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-i386.exe)

[hiper-windows-arm64.exe（Windows 平台 AArch64（Arm64））](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-arm64.exe)

**注意！下载完 Hiper 本体，请重命名为 `hiper`，接下来的教程程序名都会是他**

*小技巧：打开 Hiper 所在目录，并在文件资源管理器的导航栏中点击一下空白处显示输入框，然后输入 `cmd` 并回车，即可在 Hiper 所在目录打开 CMD。*

![](https://gitcode.net/chearlai/ff/-/raw/main/12.gif)

## Hiper 功能介绍

Hiper 一共分为两大功能：

Vlan 功能和 Chat 功能

可用命令：
   chat 通过覆盖网络聊天
   
   vlan 加入建立在覆盖网络上的虚拟专用网络.
   
   completion 为指定的shell生成自动完成脚本
   
   help 关于任何命令的帮助

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

![](https://gitcode.net/chearlai/ff/-/raw/main/13.png)

可在该命令中加入后添加调节参数，如：

```
hiper v -h
```

[Vlan 调节参数介绍（一般用户请忽略）](/Vlan 调节参数介绍.md)

**须知：**

直接使用 Vlan 功能，默认是公共渠道，公共渠道会在键入命令后随机不固定分配可用的IP，

以及在运行后 30 分钟断连，断连后 CMD/终端 中会显示如图信息，此时你可以键入命令重新加入，

![](https://gitcode.net/chearlai/ff/-/raw/main/11.png)

或者使用凭证，使用凭证不会有上述问题，默认启动的用户也可以访问你

使用凭证命令：
```
hiper v "<凭证>" 
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

施工中……

### Completion 生成自动化脚本

施工中……

## 第三方可视化 Hiper 操作

这些第三方让 Hiper 的操作更为简便，或者将 Hiper 的功能新手可使用他来初步了解。

#### hiper启动程序（仅 Windows 平台下使用）

作者：[梦游泪世](https://mcer.cn/circle-people?id=6)

可在上方链接中找到本程序的更新日志

[点击此处下载（可能不是最新版本，可在更新日志中找到最新程序下载）](https://zkitefly.github.io/hiper-d/hiper%E5%90%AF%E5%8A%A8%E7%A8%8B%E5%BA%8F.zip)

下载并解压，运行程序，即可看到如下窗口：

![](https://gitcode.net/chearlai/ff/-/raw/main/9.png)

第一次使用需要输入 `1` 回车，安装虚拟网卡

当弹出的如图弹窗显示 `Drivers installed successfully. `则代表安装成功！

*（成功后请勿重复输入“1”回车，多次操作出现问题，[详细](bat运行过多.md)）*

![](https://gitcode.net/chearlai/ff/-/raw/main/10.png)

 然后你就可以使用该程序的功能了

输入 `3` 回车，使用 Hiper 的 [Vlan](#vlan-功能介绍) 功能

输入 `2` 回车，调用凭证使用 Hiper [Vlan](#vlan-功能介绍) 功能

输入 `4` 回车，使用 Hiper 的 [Chat](#chat-功能介绍) 功能 

其他的功能直接看启动菜单就行了


