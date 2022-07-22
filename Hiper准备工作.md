# Hiper 准备工作

### 非 Windows 平台

### 以下其他平台的相应 Hiper 执行文件：

[**下载链接**](https://gitcode.net/to/hiper)

![](https://gitcode.net/chearlai/hiper-j/-/raw/main/p/28.gif)

因为 Hiper 适配了很多平台，所以需要使用相应的文件

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
</code></pre>
</details>

**Darwin（Mac OS）注意事项：你需要下载完Hiper本体的同时，也需要安装虚拟网卡，在终端 App 中输入命令进行安装 `brew install --cask tunnelblick`**

**注意！下载完 Hiper 本体，请重命名为 hiper，接下来的教程程序名都会是他**

给启动器作者小提示：

- 这个是 Hiper 本体的 sha1 列表，可以用于检查更新 Hiper `https://gitcode.net/to/hiper/-/raw/master/packages.sha1`

- https://gitcode.net/to/hiper/-/raw/master/ + <Hiper 本体名称> ，可通过上述列表获取名称，例如 `https://gitcode.net/to/hiper/-/raw/master/hiper-windows-amd64.exe`

[**返回教程**](/d.md)