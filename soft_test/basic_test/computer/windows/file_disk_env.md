# Windows-文件/磁盘/境变量
---


###1.固定ip地址
+ 方法一:桌面>>网络>>属性>>网络连接（适配器）>>双击打开网卡>>属性>>TCP/IP
+ 方法二:控制面板>>网络和 Internet>>网络和共享中心>>点击其中一个本地链接>>属性>>TCP/IP
+ 如下图:
+ ![](https://i.imgur.com/zivjXsj.png)


###2.显示 隐藏 文件和扩展名
+ 双击打开电脑>>资源管理器>>工具>>文件夹选项>>查看
+ 如下图:
+ ![](https://i.imgur.com/OqFWhO3.png)
+ ![](https://i.imgur.com/lWKvS83.png)


###3.WINDOWS  文件名
+ 文件名 + . +  拓展名 <br />
+ 常见的文件名：<br />
+ .exe <br />
![](https://i.imgur.com/X9Q7siN.png)<br />
+ .txt  文本文件<br />
![](https://i.imgur.com/scV2FDE.png)<br />
+ .bmp/.jpg/.png /.gif/.ico  图片文件<br />
![](https://i.imgur.com/O0Q2EwW.png)<br />


###4.环境变量
+ 桌面》我的电脑（计算机）》右击属性》高级系统设置》高级》环境变量
![](https://i.imgur.com/ri07MYk.png) <br /><br />
+ 环境变量作用:
	+ Path 是 windows 操作系统环境变量，Path 作用是用户在命令行窗口敲一个执行一个命令，则在 Path 变量设置的目录下依次寻找该命令对应的可执行文件，若找到，则执行，若找不到，则不执行，命令行窗口提示无效命令。


###5.关闭Windows  自带防火墙

+ 方法一:桌面》网络》属性》WINDOWS 防火墙》打开或者关闭
+ 方法二:控制面板>>系统安全>>windows防火墙
![](https://i.imgur.com/3NfF42C.png)
![](https://i.imgur.com/CIul8Vs.png)



###6.批处理文件

+ 文件的拓展名是.bat 的文件就是批处理文件，就是一种文本文件，简单来说批处理文件的作用是可以自动的连续的
执行多条 DOS 命令。


###7.磁盘分区（DISK PARITION)

+ 计算机主要存放信息的主要存储设备硬盘，硬盘不能直接使用，必须对硬盘进行分割，分割成一块一块硬盘区域就
是磁盘分区。在传统的磁盘管理中，将一个硬盘分成两大类分区，主分区（最少一个）和拓展分区（最多一个，可
以没有），主分区主要是安装操作系统，主分区能够被计算机启动的分区。


###8.文件系统（ FILE SYSTEM ）和格式化（ FORMAT ）

![](https://i.imgur.com/BHoPM1v.png)
+文件系统是操作系统用于明确磁盘或者分区上的文件的数据结构，即在磁盘上组织文件的方法，
常见文件系统的类型：windows 下 FAT32 NTFS

<table>
	<tr><td></td><td>最大支持单个文件</td><td>最大支持分区</td><td>碎片整理</td><td>分区压缩</td><td>对单个文件加密</td><td>存取速度</td></tr>
	<tr><td>FAT32</td><td>4G</td><td>32G</td><td>手动</td><td>不支持</td><td>不支持</td><td>快</td></tr>
	<tr><td>NTFS</td><td>64G</td><td>2T</td><td>自动</td><td>支持</td><td>支持</td><td>慢</td></tr>

</table>


###9.格式化
+ 定义:进行初始化的操作
+ 作用:
	1. 硬盘出厂后，必须被格式化才能够被使用，才能被系统识别
	2. 快速删除整个磁盘上的全部内容



###10.DNS （ domain name  server ）
+ DNS 是方便人们记忆，从前是没有 DNS 的，浏览网站通过 IP 地址来访问，不利于记忆，DNS 就是在这种情况诞生的。
+ http：//www.baidu.com
+ DNS 的主要作用：
	+ 域名解析服务，用于将域名解析为 IP,或者将 IP 解析为域名。客户机可以指定 DNS 来解析。
![](https://i.imgur.com/LJulUxH.png)


