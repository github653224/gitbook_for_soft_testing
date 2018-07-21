# Windows-网络技术
---


### 1. OSI模型(理论):
+ OSI 模型，即开放式通信系统互联参照模型，是国际化组织（ISO）提出的一个试图使各种计算机在世界范围内可以互联为网络的标准框架，简称 OSI。OSI 把网络协议从逻辑上分为了 7 层。<br /><br />
![](https://i.imgur.com/20LNWzI.png)<br /><br />
+ ISO7层网络模型
 	+ 应用层（Application Layer）：提供应用程序之间通信 相当于经理
	+ 表示层（Presentation Layer）：处理数据格式，数据加密 相当于公司中的助理
	+ 会话层（Session Layer）：建立维护和管理会话 相当于公司中的秘书
	+ 传输层（Transport Layer）：建立端对端的连接 相当于公司中的司机
	+ 网络层（Network Layer）：寻址和路由选择 相当于邮局中的排序工人
	+ 数据链路层（Data Link Layer）：介质访问 相当于邮局中的装拆箱工人
	+ 物理层（Physical Layer）:二进制传输 相当于邮局中的搬运工人
	+ 补充基础知识：
	+ 单位换算：
	+ 1Byte=8bit
	+ 1KB=1024Byte（字节）
	+ 1MB=1024KB
	+ 1GB=1024MB
	+ 1TB=1024GB
	+ 1PB=1024TB<br /><br />
+ 后来演化为:<br />
![](https://i.imgur.com/biKLLqt.png)<br /><br /><br />
+ OSI 数据通信原理：
	+ 数据发送端自上而下发送数据（从应用层到物理层），数据层接收端自下而上接收数据（从物理成到应用层）。
	![](https://i.imgur.com/V9lGwHG.png)<br /><br />
+ OSI 对等会话原理：
	+ 数据发送端和数据接收端只有在对等的层次上才可以进行通信，不同层次传输的数据格式不同，数据发送端每经过一层（物理层除外）都要在原数据上进行协议封装，数据接收端每经过一层，都要对原数据进行协议解封装。
+ OSI 模型的记忆法：
	+ All People Seem To Need Data Process
	+ 应用层（Application Layer）：提供应用程序之间通信 相当于经理
	+ 表示层（Presentation Layer）：处理数据格式，数据加密 相当于公司中的助理
	+ 会话层（Session Layer）：建立维护和管理会话 相当于公司中的秘书
	+ 传输层（Transport Layer）：建立端对端的连接 相当于公司中的司机
	+ 网络层（Network Layer）：寻址和路由选择 相当于邮局中的排序工人
	+ 数据链路层（Data Link Layer）：介质访问 相当于邮局中的装拆箱工人
	+ 物理层（Physical Layer）:二进制传输 相当于邮局中的搬运工人


+ OSI 模型的缺点：
	+ 协议实现起来过分复杂，而且运行效率低
	+ 协议指定的周期长，没有及时的进入市场

###2.TCP/IP模型(实际):
+ TCP/IP 协议是网络中传递信息，管理信息的一些规范。如同人与人相互交流需要遵循一定的规矩，计算机之间的相
互通信也需要共同遵循一定的规则，这些规则就称为网络协议。
+ TCP/IP 协议是网络的基础，可以说没有 TCP/IP 协议就没有互联网的今天。
![](https://i.imgur.com/laIpBPR.png)<br /><br />

<table>
	<tr><th>层次</th><th>作用</th></tr>
	<tr><td>应用层</td><td>产生数据</td></tr>
	<tr><td>传输层</td><td>拆分要传输的数据（单位：数据段）<br />添加传输层的首部：源/目的端口号<br />三次握手</td></tr>
	<tr><td>网络层</td><td>处理数据包（单位：数据包）<br />添加网络层的首部：源/目的 IP 地址</td></tr>
	<tr><td>网络接口层（链路层）</td><td>在网线上传输信号（单位：数据帧）<br />添加链路层的首部：源/目的 MAC 地址</td></tr>
	<tr><td>应用层</td><td></td></tr>
	<tr><td></td><td></td></tr>
	<tr><td></td><td></td></tr>

</table>

+ 很吊的数学公式:

Inline math: $$\int_{-\infty}^\infty g(x) dx$$

Block math:

$$
\int_{-\infty}^\infty g(x) dx
$$



Info styling

> **[info] For info**
>
> Use this for infomation messages.

Warning styling

> **[warning] For warning**
>
> Use this for warning messages.

Danger styling

> **[danger] For danger**
>
> Use this for danger messages.

Success styling

> **[success] For info**
>
> Use this for success messages.



---
disqus:
  identifier: "some-identifier"
---




