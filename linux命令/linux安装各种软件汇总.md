# 一、安装centOS

#### 1、[CentOS7](https://so.csdn.net/so/search?q=CentOS7&spm=1001.2101.3001.7020).4下载

官网下载页面地址：[Index of /](http://vault.centos.org/)

如果觉得下载比较繁琐，我已经提供了CentOS7.4的安装包:

链接：https://pan.baidu.com/s/1cRgNfZ5REf4LQMIyl5K3hQ 
提取码：lp6q 

**进入CentOS下载官网，找到CentOS7.4版本**

#### 2、CentOS7.4安装

**1、打开你的VMware Workstation Pro，并点击“创建新的虚拟机”，没有安装VMware Workstation Pro请点击[VMware Workstation 14下载与安装](https://blog.csdn.net/qq_39135287/article/details/82924547)**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**2、点选典型(推荐)(T)，并点击“下一步”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHMLy9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**3、点选稍后安装操作系统(S)，并点击“下一步”**

![](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubm0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**4、点选Linux(L)，因为我们之前下载的 CentOS-7-x86_64-DVD-1708.iso 是64位 7.4版本的，所以这里我们选择CentOS 7 64位，并点击“下一步”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxX5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**5、虚拟机名称可以更改也可以不更改看自己需求，修改虚拟机的安装路径，并点击“下一步”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MT1Mjg3,size_16,color_FFFFFF,t_70)

**6、磁盘选择默认为20.0GB，点选将虚拟磁盘存储为单个文件(O)，并点击“下一步”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTMjg3,size_16,color_FFFFFF,t_70)

**7、点击“完成”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzTM1Mjg3,size_16,color_FFFFFF,t_70)

**8、点击“编辑虚拟机设置”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10xt_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**9、点选“使用ISO映像文件(M)”，并添加我们之前下载好的CentOS-7-x86_64-DVD-1708.iso**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5M1Mjg3,size_16,color_FFFFFF,t_70)

**10、默认为NAT 模式(N)：用于共享主机的IP地址即可**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTjg3,size_16,color_FFFFFF,t_70)

**提示：11-13步骤 移除USB控制器、声卡和打印机 只是为了腾出更多的资源空间 (可以选择跳过 不移除)**

**11、选择USB 控制器，并点击“移除(R)”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3ze_16,color_FFFFFF,t_70)

**12、选择声卡，并点击“移除(R)”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,ze_16,color_FFFFFF,t_70)

**13、选择打印机，并点击“移除(R)”，最后点击“确定”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0c3,size_16,color_FFFFFF,t_70)

**14、点击“开启此虚拟机”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**15、正在开启虚拟机，鼠标移入到虚拟机中，并按下“↑”键，选择Install CentOS 7，最后按下“Enter 键”**

```markdown
    提示：  鼠标移动到虚拟机内部单击或者按下Ctrl + G，鼠标即可移入到虚拟机中

        按下Ctrl + Alt，鼠标即可移出虚拟机

    注意：  在虚拟机中的操作，鼠标必须要移入到虚拟机中，否则虚拟机感应不到，无法对其进行操作
```
![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**16、按下“Enter 键”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shad_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTMjg3,size_16,color_FFFFFF,t_70)

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0LXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**17、默认安装过程中的安装界面使用English (英语)，点击“Continue”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1,size_16,color_FFFFFF,t_70)

**18、配置时区 (DATE & TIME)**

（1）选择DATE & TIME

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjgize_16,color_FFFFFF,t_70)

（2）时区设置为 Region：Asia  City：Shanghai

 日期和时间 设置与自己的电脑[时间同步](https://so.csdn.net/so/search?q=时间同步&spm=1001.2101.3001.7020)，最后点击“Done”

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,ow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTjg3,size_16,color_FFFFFF,t_70)

**19、设置软件选择 (SOFTWARE SELECTION)**

（1）选择SOFTWARE SELECTION

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（2）点击勾选 Compatibility Libraries 和 Development Tools

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,sizedd_16,color_FFFFFF,t_70)

如果希望安装带有界面的CentOS，请在左边Base Environment中，选择Server with GUI(带图形用户界面的服务器)，默认为Minimal Install (最小安装)，提示：如果安装有界面版本的，在如下的第22步骤中的操作会有所不同 (安装有界面版本的其实用处不大，都是可以通过命令行来设置的)，这里我没有安装有界面版本的
![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,ffsize_16,color_FFFFFF,t_70)

**20、设置安装位置 (INSTALLATION DESTINATION)**

（1）选择INSTALLATION DESTINATION

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHy9ibG9nLmNzZG4ubmV0L3FxXzMM1Mjg3,size_16,color_FFFFFF,t_70)

（2）点选 I will configuire parttioning，然后再点击“Done”

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_acHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（3）更改模式，标准分区Standard Partition，点击“+”按钮添加分区

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,tHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（4）添加 /boot分区，大小300MB，Add mount point

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5nadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVcHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（5）添加 swap分区，一般情况是物理内存的2倍大小，用于物理内存不足时使用，但可能造成系统不稳定，所以看情况，可以设置小一点，甚至设置为0MB，这里我设置为512MB，Add mount point

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（6）增加根分区，不填写大小，即默认剩余的空间都给根分区，Add mount point

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZy9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（7）点击“Done”

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（8）点击“Accept Changes”

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpd4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**21、点击“Begin Installation”，开始安装**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**22、设置系统用户root的密码 (ROOT PASSWORD)**

（1）选择ROOT PASSWORD

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（2）为root设置密码 (密码长度最好不要小于6位数)，然后点击“Done”

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**23、等待安装完成，然后点击“Reboot”**

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

#### 3、CentOS7.4基本设置

##### 1、登录CentOS，默认账号为root，密码为 你在前面安装时设置的root密码

提示：在输入密码时，linux为了安全起见，是看不到你输入的密码。同时，如果是使用的是键盘右边的数字键盘输入密码的话，建议查看一下，数字键盘是否开启 (建议使用字母按键上面一排的 数字键输入密码)
![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

##### **2、配置IP地址，网关**

~~~markdown
 1. cd /etc/sysconfig/network-scripts/    //进入到network-scripts目录下 
 2.  vi ifcfg-ens32  //编辑配置文件 
 3. //修改以下内容
 4.  BOOTPROTO=static  //启用静态IP地址
 5.   ONBOOT=yes      //开启自动启用网络连接
 6. //添加以下内容
 7.  IPADDR=192.168.23.124    //设置IP地址
 8.  NETMASK=255.255.255.0   //子网掩码
 9. GATEWAY=192.168.23.2   //设置网关

~~~

~~~markdown
`提示：这里vi编辑器打开文件之后，是进入到了文件的命令模式，需要我们按下 i键 或者 a键进入到编辑模式，就可以开始编辑文件了，编辑完成之后，按下Esc键进入到命令模式，然后在按下Shift键 和 :键(冒号) 进入到末行模式，再按下w键 和 q键表示保存并退出，最后按下Enter回车键即可。
~~~

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVpdGbmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](D:\develop\zto\codes\jcj-notes\jcjNotes\linux命令\linux_imag\watermark,type_ZmFuZ3poZW5naGVp9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)