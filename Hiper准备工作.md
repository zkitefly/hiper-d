# Hiper 准备工作



### 非 Windows 平台下运行

非 Windows 下，无需安装虚拟网卡

[在此处选择相应版本的 Hiper 下载](https://gitcode.net/to/hiper)

以下是这些系统的相应 Hiper 执行文件：

(带有“←”为该平台一般常用的 Hiper 执行程序)

```
Darwin（Mac OS）
   \
   hiper-darwin-amd64   
   hiper-darwin-arm64   ←
Freebsd
   \
   hiper-freebsd-amd64   ←
   hiper-freebsd-arm7
   hiper-freebsd-arm64
   hiper-freebsd-i386
WebAssembly
   \
   hiper-js.wasm   ←
Linux/Linux 发行版
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
OpenBSD
   \
   hiper-openbsd-amd64
   hiper-openbsd-arm7
   hiper-openbsd-arm64
```
其中，这些对应的平台还有架构的相应适配，由于系统过多，本文章仅列举出几个平台架构查询方法，其他平台的架构查询请自行寻找方法，或[联系我](/d.md#%E6%8F%90%E7%A4%BA)

Darwin（Mac OS）：
- 在左上角，点击Apple菜单>关于本机

![](https://gitcode.net/chearlai/ff/-/raw/main/5.png)

- 在“概览”页中查看“芯片”或“处理器”

![](https://gitcode.net/chearlai/ff/-/raw/main/6.png)

Intel处理器，则使用 `hiper-darwin-amd64`

Apple-M系列处理器（如M1），则使用 `hiper-darwin-arm64`

Linux/Linux 发行版：
- 启动终端/命令行，输入命令 `arch` 并回车

![](https://gitcode.net/chearlai/ff/-/raw/main/7.png)

- 在命令行结果中查看系统架构信息

X86_64，则使用 `hiper-linux-amd64`

X86，则使用 `hiper-linux-i386`

*其他的大致是可以对应 Hiper 名称上的架构名（因为我也不知道其他架构下会输出啥……）*

**注意！下载完 Hiper 本体，请重命名为 hiper，接下来的教程程序名都会是他**

[返回教程](/d.md)