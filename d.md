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

## Hiper 使用

### 终端命令

#### 下载

在 Gitcode 仓库下载 Hiper 本体程序：

[https://gitcode.net/to/hiper](https://gitcode.net/to/hiper)

![](/p/2.png)

下载完后解压，你会看到如下文件：

```
[hiper-master]（文件夹）
   \
   [windows-tap]（文件夹）
      \
      FIRST_RUN_THIS_SCRIPT.bat
      OemVista.inf
      packages.sha1
      tap0901.cat
      tap0901.sys
      tap_install.exe
   hiper-darwin-amd64
   hiper-darwin-arm64
   hiper-freebsd-amd64
   hiper-freebsd-arm7
   hiper-freebsd-arm64
   hiper-freebsd-i386
   hiper-js.wasm
   hiper-linux-amd64
   hiper-linux-arm7
   hiper-linux-arm64
   hiper-linux-i386
   hiper-linux-mips
   hiper-linux-mips64
   hiper-linux-mips64le
   hiper-linux-mipsle
   hiper-linux-ppc64
   hiper-linux-ppc64le
   hiper-openbsd-amd64
   hiper-openbsd-arm7
   hiper-openbsd-arm64
   hiper-openbsd-i386
   hiper-windows-amd64.exe
   hiper-windows-arm64.exe
   hiper-windows-i386.exe
   packages.sha1
```   

**注意：如果在下方的教程中出现问题，请重新在此下载 Hiper！**
#### Windows 平台下使用

Windows 系统下需要选择 `FIRST_RUN_THIS_SCRIPT.bat` 右键选择 **以管理员身份运行**，安装 Hiper 所需的虚拟网卡！（请勿重复运行，多次操作出现问题，[详细](bat运行过多.md)）
```
[hiper-master]（文件夹）
   \
   [windows-tap]（文件夹）
      \
      FIRST_RUN_THIS_SCRIPT.bat   ←
      OemVista.inf
      packages.sha1
      tap0901.cat
      tap0901.sys
      tap_install.exe

……      
```
![](/p/3.png)

![](/p/4.png)

#### 非 Windows 平台下运行

非 Windows 下，无需安装虚拟网卡，但需要超级用户权限

以下是这些系统的相应 Hiper 执行文件：

(带有“←”为该平台一般常用的 Hiper 执行程序)

```
[Darwin（Mac OS）](https://cn.bing.com/search?q=Darwin+Mac+OS)
   \
   hiper-darwin-amd64   
   hiper-darwin-arm64   ←
[Freebsd](https://cn.bing.com/search?q=Freebsd)
   \
   hiper-freebsd-amd64   ←
   hiper-freebsd-arm7
   hiper-freebsd-arm64
   hiper-freebsd-i386
[WebAssembly](https://cn.bing.com/search?q=WebAssembly)
   \
   hiper-js.wasm   ←
[Linux/Linux 发行版](https://cn.bing.com/search?q=Linux-发行版)
   \
   hiper-linux-amd64   ←
   hiper-linux-arm7
   hiper-linux-arm64
   hiper-linux-i386
   hiper-linux-mips  
   hiper-linux-mips64
   hiper-linux-mips64le
   hiper-linux-mipsle
   hiper-linux-ppc64
   hiper-linux-ppc64le
[OpenBSD](https://cn.bing.com/search?q=OpenBSD)
   \
   hiper-openbsd-amd64
   hiper-openbsd-arm7
   hiper-openbsd-arm64
```
其中，这些对应的平台还有架构的相应适配，由于系统过多，本文章仅列举出几个平台架构查询方法，其他平台的架构查询请自行寻找方法，或[联系我]()

Darwin（Mac OS）：
- 在左上角，点击Apple菜单>关于本机

![](/p/5.png)

- 在“概览”页中查看“芯片”或“处理器”

![](/p/6.png)

Intel处理器，则使用 `hiper-darwin-amd64`

Apple-M系列处理器（如M1），则使用 `hiper-darwin-arm64`

Linux/Linux 发行版：
- 启动终端/命令行，输入命令 `uname -a` 并回车

![](/p/7.png)

- 在命令行结果中查看系统架构信息

X86_64，则使用 `hiper-linux-amd64`

X86，则使用 `hiper-linux-i386`




### 第三方可视化操作 

#### hiper启动程序（仅 Windows 下使用）

作者：[梦游泪世](https://mcer.cn/circle-people?id=6)

可在上方链接中找到本程序的更新日志

[点击此处下载（可能不是最新版本，可在更新日志中找到最新程序下载）](/hiper%E5%90%AF%E5%8A%A8%E7%A8%8B%E5%BA%8F.zip)



