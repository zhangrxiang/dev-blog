# Linux Commond


```shell
1.ls [选项] [目录名 | 列出相关目录下的所有目录和文件

2.mv [选项] 源文件或目录 目录或多个源文件 | 移动或重命名文件

3.cp [选项] 源文件或目录 目录或多个源文件 | 将源文件复制至目标文件，或将多个源文件复制至目标目录。

4.scp [参数] [原路径] [目标路径] | 在Linux服务器之间复制文件和目录

5.rm [选项] 文件 | 删除文件

6.touch [选项] 文件 | 创建空文件或更新文件时间

7.pwd 查看当前所在路径

8.cd 改变当前目录

9.mkdir [选项] 目录… | 创建新目录

11.rm [选项] 文件… | 一个或多个文件或目录

12.echo：显示内容

13.cat [选项] [文件]..| 一次显示整个文件或从键盘创建一个文件或将几个文件合并成一个文件

14.tac | 反向显示

15.more | 按页查看文章内容，从前向后读取文件，因此在启动时就加载整个文件

16.less | 可前后移动地逐屏查看文章内容，在查看前不会加载整个文件

17.nl [选项]… [文件]… | 将输出内容自动加上行号

18.head [参数]… [文件]… | 显示档案开头，默认开头10行

19.tail [必要参数] [选择参数] [文件] | 显示文件结尾内容

20.vi 编辑文件

21.which 可执行文件名称 | 查看可执行文件的位置，在PATH变量指定的路径中查看系统命令是否存在及其位置

22.whereis [-bmsu] [BMS 目录名 -f ] 文件名| 定位可执行文件、源代码文件、帮助文件在文件系统中的位置

23.locate | 通过搜寻数据库快速搜寻档案

24.find find [PATH] [option] [action] | 在文件树种查找文件，并作出相应的处理

25.file | 判断文件类型

26.gzip [-cdtv#] 檔名 | 压缩、解压缩，源文件都不再存在

27.gunzip | 解压缩

28.bzip2 | 压缩、解压缩

29.bzcat 读取数据而无需解压

30.tar [主选项+辅选项] 文件或者目录 | 多个目录或档案打包、压缩成一个大档案

31.exit 退出当前shell

32.logout 退出登录shell

33.shutdown -h now

34.users 显示当前登录系统地用户

35.who 登录在本机的用户与来源

36.w 登录在本机的用户及其运行的程序

37.write 给当前联机的用户发消息

38.wall 给所有登录再本机的用户发消息

39.last 查看用户的登陆日志

40.lastlog 查看每个用户最后的登陆时间

41.finger [选项] [使用者] [用户@主机] | 查看用户信息

42.hostname 查看主机名

43.alias ii = “ls -l” | 添加别名

44.unalias ii | 清除别名

45.useradd [-u UID] [-g 初始群组] [-G 次要群组] [-c 说明栏] [-d 家目录绝对路径] [-s shell] 使用者账号名 | 新增用户

46.passwd | 修改密码

47.userdel 删除用户

48.chage [-ldEImMW] 账号名 | 修改用户密码的相关属性

49.usermod [-cdegGlsuLU] username | 修改用户的相关属性

50.id [username] | 查看用户相关的id信息，还可以用来判断用户是否存在

51.groups 查看登陆用户支持的群组， 第一个输出的群组为有效群组

52.newgrp 切换有效群组

53.groupadd [-g gid] 组名 | 添加组

54.groupmod [-g gid] [-n group_name] 群组名 | 修改组信息

55.groupdel [groupname] | 删除群组

56.gpasswd | 群组管理员功能

57.chfn修改个人信息

58.mount [-t vfstype] [-o options] device dir

59.umount 取消挂载

60.cut 分割

61.sort 排序

62.wc 统计指定文件中的字节数、字数、行数, 并将统计结果显示输出

63.uniq 去除文件中相邻的重复行

64.set 显示环境变量和普通变量

65.env 显示环境变量

66.export 把普通变量变成环境变量

67.unset 删除一个环境变量

68.read

69.declare、typeset

70.ulimit 限制使用者的某些系统资源

71.df [选项] [文件] | 显示指定磁盘文件的可用空间,如果没有文件名被指定，则所有当前被挂载的文件系统的可用空间将被显示

72.du [选项] [文件] | 显示每个文件和目录的磁盘使用空间

73.ln [参数] [源文件或目录] [目标文件或目录] | 某一个文件在另外一个位置建立一个同步的链接

74.diff [参数] [文件1或目录1] [文件2或目录2] | 比较单个文件或者目录内容

75.date [参数]… [+格式] | 显示或设定系统的日期与时间

76.cal [参数] 月份] [年份] | 查看日历

78.top [参数] | 显示当前系统正在执行的进程的相关信息，包括进程ID、内存占用率、CPU占用率等

79.kill [参数] [进程号] | 杀死进程

80.free [参数] | 显示Linux系统中空闲的、已用的物理内存及swap内存,及被内核使用的buffer

81.vmstat | 对操作系统的虚拟内存、进程、CPU活动进行监控

82.iostat [参数] [时间t] [次数n](每隔t时间刷新一次，最多刷新n次)| 对系统的磁盘操作活动进行监视,汇报磁盘活动统计情况，同时也会汇报出CPU使用情况

83.watch [参数] [命令] |重复执行某一命令以观察变化

84.at [参数] [时间] | 在一个指定的时间执行一个指定任务，只能执行一次

85.crontab | 定时任务调度

86.ifconfig [网络设备] [参数] | 查看和配置网络设备

87.route | 显示和操作IP路由表

88.ping [参数] [主机名或IP地址] | 测试与目标主机的连通性

89.netstat | 显示与IP、TCP、UDP和ICMP协议相关的统计数据

90.telnet [参数] [主机] | 用于远程登录，采用明文传送报文，安全性不好

91.rcp [参数] [源文件] [目标文件] | 远程文件拷贝

93.awk

94.sed 对数据行进行替换、删除、新增、选取等操作

95.paste 合并文件，需确保合并的两文件行数相同

96.su [参数] user | 切换登陆

97.sudo | 以特定用户的权限执行特定命令
```


## See
- <http://blog.csdn.net/boshuzhang/article/details/51122457>

### *All rights reserved*

