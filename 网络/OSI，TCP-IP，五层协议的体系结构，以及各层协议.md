- OSI:应用层、表示层、会话层、网络层、传输层、数据链路层、物理层
- tcp/ip:应用层、传输层、网际层、网络接口层
- 5层协议：应用层、网络层、传输层、数据链路层、物理层



##物理层：
- RJ45( 布线系统 中 信息插座 连接器的一种) , 
- CLOCK,
- IEEE802.3、( 通常指 以太网 。一种 网络协议 。描述 物理层 和 数据链路层 的MAC子层的实现方法 )
- （中继器，集线器）

##数据链路层
- ppp, ( Point to Point Protocol, 是为在同等 单元 之间传输 数据包 这样的简单链路设计的 链路层 协议 )
- FR, ( Frame Relay的缩写，是一种以帧为数据单位的传输模式 )
- HDLC,( 高级数据链路控制 ,  是一个在同步网上传输 数据、面向比特的 数据链路层 协议 )
- VLAN, (虚拟局域网)
- MAC、( MAC地址、 物理地址 )
- (网桥，交换机）

##网络层：
- IP、
- ICMP,( Internet控制 报文 协议。它是 TCP/IP协议族 的一个子协议 )
- ARP,
- RARP,
- OSPF, ( Open Shortest Path First 开放式最短路径优先 ）是一个 内部网关协议 )
- IPX, ( 互联网 数据包 交换协议  )
- RIP, ( 路由信息协议 )
- IGRP,( 一种内部网关 路由 协议 )
- （路由器）

##传输层：
- TCP,
- UDP，
- SPX,( 序列 分组交换 协议 )

##会话层：
- NFS, ( 网络文件系统 )
- SQL, 
- NETBIOS, ( 主要用于数十台计算机的 小型局域网 )
- RPC( 远程过程调用 协议 )

##表示层：
- JPEG, 
- MPEG,( 动态图像专家组 )
- ASII

##应用层：
- FTP, 
- DNS, 
- Telnet, 
- SMTP, ( 简单邮件传输协议 )
- HTTP, 
- WWW, 
- NFS

---

##每一层的作用：
- 物理层：通过媒介传输比特，确定机械及电器规范（比特Bit).
- 数据链路层：将比特组装成帧和点到点的传递（帧Frame)
- 网络层：负责数据包从源到宿的传递和网际互连（包Packet）
- 传输层：提供端到端的可靠报文和错误恢复（段Segment)
- 会话层：建议，管理和终止会话（会话协议数据单元SPDU)
- 表示层：对数据进行翻译、加密和压缩（表示协议数据单元PPDU）
- 应用层：允许访问OSI环境的手段（应用协议数据单元APDU)

