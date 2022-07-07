# Hiper

![](/p/1.png)

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

（

## Hiper 准备工作

以下列举的是 Windows 平台的准备工作，非 Windows 平台请[访问此](https://zkitefly.github.io/hiper-d/Hiper%20%E5%87%86%E5%A4%87%E5%B7%A5%E4%BD%9C.html)

### 下载
下载两个文件：
必须下载:
[windows-tap](https://zkitefly.github.io/hiper-d/windows-tap.7z)
Hiper 本体（按照你的计算机架构下载，**不知道下那个就下载 hiper-windows-amd64.exe**）：
[hiper-windows-amd64.exe（Windows 平台 X86_64位 ，☆一般选择此下载☆）](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-amd64.exe)
[hiper-windows-i386.exe（Windows 平台 X86_32位）](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-i386.exe)
[hiper-windows-arm64.exe（Windows 平台 AArch64（Arm64））](https://gitcode.net/to/hiper/-/raw/master/hiper-windows-arm64.exe)

**注意！下载完 Hiper 本体，请重命名为 `hiper`，接下来的教程程序名都会是他**

### Windows 平台下使用

Windows 系统下需要选择 `FIRST_RUN_THIS_SCRIPT.bat` 右键选择 **以管理员身份运行**，安装 Hiper 所必须使用的虚拟网卡！（请勿重复运行，多次操作出现问题，[详细](bat运行过多.md)）

![](/p/3.png)

![](/p/4.png)

### 注意事项

当你已经在在上方的 准备工作 中准备好了之后，将适合你平台的 hiper 程勋统一修改名字成 `hiper`，接下来的

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

### Vlan 使用

使用命令使用 Vlan 功能：

```
hiper v
```
可在该命令中加入后添加调节参数，如：
```
hiper v
```
**注意！非 Windows 平台需要Root权限，及输入以下命令：**
```
sudo hiper v
```

[Vlan 调节参数介绍（一般用户请忽略）](/Vlan%20%E8%B0%83%E8%8A%82%E5%8F%82%E6%95%B0%E4%BB%8B%E7%BB%8D.md)


## 第三方可视化 Hiper 操作

这些第三方为 Hiper 的操作更为简便，或者将 Hiper 的功能新手可使用他来初步了解。

#### hiper启动程序（仅 Windows 下使用）

作者：[梦游泪世](https://mcer.cn/circle-people?id=6)

可在上方链接中找到本程序的更新日志

[点击此处下载（可能不是最新版本，可在更新日志中找到最新程序下载）](https://zkitefly.github.io/hiper-d/hiper%E5%90%AF%E5%8A%A8%E7%A8%8B%E5%BA%8F.zip)

下载并解压，运行程序，



