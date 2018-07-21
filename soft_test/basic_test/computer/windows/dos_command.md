# Windows-Dos命令行
---

## windows 控制台：DOS命令行:

<table>
	<tr><th>命令</th><th>作用描述</th><th>举例</th></tr>
	<tr><td>cd</td><td>进入到某个目录</td><td>cd 路径 <br/>路径可以分为绝对路径和相对路径<br/>绝对路径：C:\WINDOWS\SYSTEM <br/>相对路径：<br/>. 当前路径 <br/>.. 上一级路径</td></tr>
	<tr><td>ping</td><td>网络是否连接</td><td>ping 192.168.1.6 查看本机和 6 的机器网络是否正常连接</td></tr>
	<tr><td>ipconfig</td><td>查看 ip 地址</td><td>ipconfig 查看的是当前的 ip 地址<br/>参数：<br/>ipconfig /? 查看 ipconfig 命令的帮助<br/>ipconfig /all 查看当前所有的网络信息</td></tr>
	<tr><td>dir</td><td>显示当前文件夹（目录）的内容</td><td>dir /p 分屏显示内容 <br />dir /w 宽列表格显示内容</td></tr>
	<tr><td>cls</td><td>清除屏幕</td><td></td></tr>
	<tr><td>ctrl + c</td><td>终止命令执行</td><td></td></tr>
	<tr><td>mkdir </td><td>新建文件夹（目录）</td><td>mkdir c:\test</td></tr>
	<tr><td>edit</td><td>新建文件，编辑文件</td><td>edit 文件名</td></tr>
	<tr><td>tree</td><td>以树形结构显示目录</td><td>tree c:\aaa</td></tr>
	<tr><td>del</td><td>删除文件</td><td>del c:\aaa\yyy\abc.txt</td></tr>
	<tr><td>rmdir</td><td>删除空目录，空文件夹</td><td>rmdir c:\aaa\yyy</td></tr>
	<tr><td>rd </td><td>删除非空目录，非空文件夹</td><td>rd c:\aaa\yyy</td></tr>
	<tr><td>rename</td><td>重命名（当前文件夹）</td><td>rename abc.txt f.txt</td></tr>
	<tr><td>copy</td><td>复制文件</td><td>copy c:\hhh\f.txt c:\aaa</td></tr>
	<tr><td>type</td><td>查看文件内容</td><td>type c:\aaa\a.txt</td></tr>
	<tr><td>exit</td><td>退出控制台窗口</td><td></td></tr>
	<tr><td>shutdonw</td><td>关机</td><td></td></tr>
	<tr><td>netstat</td><td>查看本地计算机使用的网络服务情况</td><td>netstat –ano 查看所有端口的使用情况<br />netstat –ano | findstr “80” 查看指定端口 80 的占用情况</td></tr>
	<tr><td>tracert</td><td>跟踪路由器（自己访问网站，到底经过了哪些路由器）</td><td>tracert www.baidu.com</td></tr>
	<tr><td>attrib</td><td>指定或者显示文件的属性命令</td><td>A 表示文件存档属性<br />S 表示系统属性，系统文件是操作系统的一部分，防止误删除，+表示增加属性，-表示取消属性<br />H 表示隐藏属性，文件在系统当中是隐藏的，在默认的情况下，用户不能看见这些文件<br />R 表示只读属性，表示该文件不能被更改</td></tr>
</table>

<a href="https://www.cnblogs.com/defen/p/5618226.html">点击更多Dos命令</a> <br />
