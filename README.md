trojan
======

trojan which can pass many security software on windows

* 自启动和进程驻留
* 自动关机
* 搜索文件
* 截屏
* 添加用户
* 获取主机信息

# 总体流程

![1.png](https://github.com/wcc526/trojan/raw/master/docs/1.png)

# 测试环境

![2.png](https://github.com/wcc526/trojan/raw/master/docs/2.png)

# 主界面

![3.png](https://github.com/wcc526/trojan/raw/master/docs/3.png)

# 配置探针界面

![4.png](https://github.com/wcc526/trojan/raw/master/docs/4.png)

# 自启动和进程驻留

一个普通的弹出对话框程序，在探针的控制下，使用能够自启动和进程驻留

* 操作系统: Windows 7 家庭普通版
* 杀毒软件: 360 安全卫士 v8.6 正式版 360 杀毒 v3.0 正式版

![5.png](https://github.com/wcc526/trojan/raw/master/docs/5.png)

# 自动关机

每次开机过大约30秒后，都会自动关机,造成被控端的用户无法正常使用

* 操作系统: Windows 2008 Server DataCenter SP2
* 杀毒软件: 金山毒霸 2012 + 金山卫士 4.0

![6.png](https://github.com/wcc526/trojan/raw/master/docs/6.png)

即使把探针删除重启之后，被控端重启之后，仍会自动关机

![7.png](https://github.com/wcc526/trojan/raw/master/docs/7.png)

# 搜索文件

搜索所有以.txt 结尾的路径,把结果放入文件,上传到主控端

* 操作系统: Windows 7 企业版 SP1
* 杀毒软件: Dr.Web Security Space Pro

![8.png](https://github.com/wcc526/trojan/raw/master/docs/8.png)

# 截屏

对被控端进行截屏

* 操作系统: Windows XP PRO3
* 杀毒软件: 小红伞 Avira Antivirus Premium 2012

![9.png](https://github.com/wcc526/trojan/raw/master/docs/9.png)

# 添加用户

在被控端的机子上添加一个用户名为kpss,密码为12345 的管理员用户

* 操作系统: Windows XP PRO 3
* 杀毒软件: 卡巴斯基安全部队 2012

![10.png](https://github.com/wcc526/trojan/raw/master/docs/10.png)

# 获取主机信息

获取详细的主机信息

* 操作系统: Windows Vista Business SP2
* 杀毒软件: 诺顿 360 全能特警 6.0

![11.png](https://github.com/wcc526/trojan/raw/master/docs/11.png)
