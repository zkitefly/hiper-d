```
      --community string 要加入的社区 ID（默认为“公共”）
      
      --dev string 给 TAP 设备的名称（即 hiper0）（默认是自动生成的；仅在 Linux、macOS 和 Windows 平台下支持）
      
      --force-relay 强制使用中继服务器
      
      -h, --help vlan 的帮助
      
      --ice strings 逗号分隔的 STUN 服务器列表（格式为 stun:host:port）和要使用的中继服务器（格式为 
      username:credential@turn:host:port）（即 username:credential@turn:global.turn。 twilio.com:3478?transport=tcp) (默认 [stun:stun.the.bb:3478,stun:stun.l.google.com:19302])
      
      --ips 字符串 以逗号分隔的 IP 网络列表，用于从 TUN 设备声明 IP 地址并提供给 TUN 设备（在 Windows 平台下，仅支持一个 IPv4 和一个 IPv6 地址；在 macOS 平台下，忽略 IPv4 地址）（默认 [6.0 .0.0/7])
      
      --key string 社区的加密密钥（默认为“null”）
      
      --mac 字符串 MAC 地址，提供给 TAP 设备（即 3a:f8:de:7b:ef:52）（默认是自动生成的；仅在 Linux 平台下支持）
      
      --parallel int 用于解码帧的线程数（默认 4）
      
      --password string 社区密码（默认为“null”）
      
      --signal-addr string 信令地址（默认“wss://signaling.mcer.cn/”）
      
      --static 尝试静态声明在 --ips 标志中指定的确切 IP，而不是从指定网络中随机选择一个
      
      --timeout duration 等待连接的时间（默认 10 秒）
      
      -t, --token string 用户认证密钥（通过 https://mcer.cn/shop 或在QQ群（在 # 提示 中有提到）里询问获取 token）
```