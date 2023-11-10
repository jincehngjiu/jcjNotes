# 一、安装centOS

#### 1、[CentOS7](https://so.csdn.net/so/search?q=CentOS7&spm=1001.2101.3001.7020).4下载

官网下载页面地址：[Index of /](http://vault.centos.org/)

如果觉得下载比较繁琐，我已经提供了CentOS7.4的安装包:

链接：https://pan.baidu.com/s/1cRgNfZ5REf4LQMIyl5K3hQ 
提取码：lp6q 

**进入CentOS下载官网，找到CentOS7.4版本**

#### 2、CentOS7.4安装

**1、打开你的VMware Workstation Pro，并点击“创建新的虚拟机”，没有安装VMware Workstation Pro请点击[VMware Workstation 14下载与安装](https://blog.csdn.net/qq_39135287/article/details/82924547)**

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**2、点选典型(推荐)(T)，并点击“下一步”**

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shazZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**3、点选稍后安装操作系统(S)，并点击“下一步”**

![](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,sha9nLmNzZG4ubm0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**4、点选Linux(L)，因为我们之前下载的 CentOS-7-x86_64-DVD-1708.iso 是64位 7.4版本的，所以这里我们选择CentOS 7 64位，并点击“下一步”**

![img](linux_imag/watermark,type_ZmFuZ3poZWFxX5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**5、虚拟机名称可以更改也可以不更改看自己需求，修改虚拟机的安装路径，并点击“下一步”**

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVp5MT1Mjg3,size_16,color_FFFFFF,t_70)

**6、磁盘选择默认为20.0GB，点选将虚拟磁盘存储为单个文件(O)，并点击“下一步”**

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGG9nLmNzZG4ubmV0L3FxXzM5MTMjg3,size_16,color_FFFFFF,t_70)

**7、点击“完成”**

![img](linux_imag/watermark,type_ZmFuZ3poZW5n4ubmV0L3FxXzTM1Mjg3,size_16,color_FFFFFF,t_70)

**8、点击“编辑虚拟机设置”**

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,M5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**9、点选“使用ISO映像文件(M)”，并添加我们之前下载好的CentOS-7-x86_64-DVD-1708.iso**

![img](linux_imag/watermark,type_ZmFuZ3poZWtext_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5M1Mjg3,size_16,color_FFFFFF,t_70)

**10、默认为NAT 模式(N)：用于共享主机的IP地址即可**

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpZG4ubmV0L3FxXzM5MTjg3,size_16,color_FFFFFF,t_70)

**提示：11-13步骤 移除USB控制器、声卡和打印机 只是为了腾出更多的资源空间 (可以选择跳过 不移除)**

**11、选择USB 控制器，并点击“移除(R)”**

![img](linux_imag/watermark,type_ZmFuZ3poZW5nabG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3ze_16,color_FFFFFF,t_70)

**12、选择声卡，并点击“移除(R)”**

![img](linux_imag/watermark,type_ZmFuZ3poZWibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,ze_16,color_FFFFFF,t_70)

**13、选择打印机，并点击“移除(R)”，最后点击“确定”**

![img](linux_imag/watermark,type_ZmFuZ3c3,size_16,color_FFFFFF,t_70)

**14、点击“开启此虚拟机”**

![img](linux_imag/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0ze_16,color_FFFFFF,t_70)

**15、正在开启虚拟机，鼠标移入到虚拟机中，并按下“↑”键，选择Install CentOS 7，最后按下“Enter 键”**

```markdown
    提示：  鼠标移动到虚拟机内部单击或者按下Ctrl + G，鼠标即可移入到虚拟机中

        按下Ctrl + Alt，鼠标即可移出虚拟机

    注意：  在虚拟机中的操作，鼠标必须要移入到虚拟机中，否则虚拟机感应不到，无法对其进行操作
```
![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,texte_16,color_FFFFFF,t_70)

**16、按下“Enter 键”**

![img](linux_imag/watermark,type_ZmFuZ3poZWzZG4ubmV0L3FxXzM5MTMjg3,size_16,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmF6Ly9ibG9nLmNzZG4ubmV0LXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**17、默认安装过程中的安装界面使用English (英语)，点击“Continue”**

![img](linux_imag/watermark,type_ZmFuZ3poZZG4ubmV0L3FxXzM5MTM1,size_16,color_FFFFFF,t_70)

**18、配置时区 (DATE & TIME)**

（1）选择DATE & TIME

![img](linux_imag/watermark,type_ZmFuZ3poZW5na9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjgize_16,color_FFFFFF,t_70)

（2）时区设置为 Region：Asia  City：Shanghai

 日期和时间 设置与自己的电脑[时间同步](https://so.csdn.net/so/search?q=时间同步&spm=1001.2101.3001.7020)，最后点击“Done”

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,ow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmFFFF,t_70)

**19、设置软件选择 (SOFTWARE SELECTION)**

（1）选择SOFTWARE SELECTION

![img](linux_imag/watermark,type_ZmFuZ3po9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（2）点击勾选 Compatibility Libraries 和 Development Tools

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shzM5MTM1Mjg3,sizedd_16,color_FFFFFF,t_70)

如果希望安装带有界面的CentOS，请在左边Base Environment中，选择Server with GUI(带图形用户界面的服务器)，默认为Minimal Install (最小安装)，提示：如果安装有界面版本的，在如下的第22步骤中的操作会有所不同 (安装有界面版本的其实用处不大，都是可以通过命令行来设置的)，这里我没有安装有界面版本的
![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shzM5MTM1Mjg3,ffsize_16,color_FFFFFF,t_70)

**20、设置安装位置 (INSTALLATION DESTINATION)**

（1）选择INSTALLATION DESTINATION

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHy9ibG9nLmNlor_FFFFFF,t_70)

（2）点选 I will configuire parttioning，然后再点击“Done”

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadoMjg3,size_16,color_FFFFFF,t_70)

（3）更改模式，标准分区Standard Partition，点击“+”按钮添加分区

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdG0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

（4）添加 /boot分区，大小300MB，Add mount point

![img](linux_imag/watermark,type_ZmFuZ3poZW5nadow_10,text_aHR0cHM6Ly9ibG9nLmNzZGTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](linux_imag/size_16,color_FFFFFF,t_)

（5）添加 swap分区，一般情况是物理内存的2倍大小，用于物理内存不足时使用，但可能造成系统不稳定，所以看情况，可以设置小一点，甚至设置为0MB，这里我设置为512MB，Add mount point

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGHR0cHM6Ly9ibG9nLmNzZG4ubMjg3,size_16,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmFuZ3poZR0cHM6Ly9ibG9nLmNzZGTM1Mjg3,size_16,color_FFFFFF,t_70)

（6）增加根分区，不填写大小，即默认剩余的空间都给根分区，Add mount point

![img](linux_imag/ZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZFF,t_70)

（7）点击“Done”

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdV0L3Fxor_FFFFFF,t_70)

（8）点击“Accept Changes”

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVTM1Mjg3,size_16,color_FFFFFF,t_70)

**21、点击“Begin Installation”，开始安装**

![img](linux_imag/watermark,type_ZmFuZ3poZW5n1Mjg3,size_16,color_FFFFFF,t_70)

**22、设置系统用户root的密码 (ROOT PASSWORD)**

（1）选择ROOT PASSWORD

![img](linux_imag/size_16,color_FF,t_)

（2）为root设置密码 (密码长度最好不要小于6位数)，然后点击“Done”

![img](linux_imag/watermark,type_ZmFuZM6Ly9ibG9nLm6,color_FFFFFF,t_70)

**23、等待安装完成，然后点击“Reboot”**

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdNzor_FFFFFF,t_70)

#### 3、CentOS7.4基本设置

##### 1、登录CentOS，默认账号为root，密码为 你在前面安装时设置的root密码

提示：在输入密码时，linux为了安全起见，是看不到你输入的密码。同时，如果是使用的是键盘右边的数字键盘输入密码的话，建议查看一下，数字键盘是否开启 (建议使用字母按键上面一排的 数字键输入密码)
![img](linux_imag/watermark,type_6Ly9ibG9nLmNzZG4ubm6,color_FFFFFF,t_70)

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

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGLmNzZGcolor_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGbmV0L6,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmFuZ3poZMjg3,size_16,color_FFFFFF,t_70)

~~~markdown
`那么看到这里，就会有小伙伴有疑问了，为什么虚拟机的ip地址设置为192.168.23.124、子网掩码设置为255.255.255.0 和 网关设置为192.168.23.2 而不设置为其他的地址呢，比如说把虚拟机的ip地址设置为192.168.24.168呢，那么我们又该如何设置自己的ip地址、子网掩码和网关呢？带着这些问题，我来为大家一一解答
~~~

###### **问题一：如何设置我们的子网掩码和网关，为什么我的 子网掩码为255.255.255.0 和 网关为192.168.23.2** 

1、点击编辑(E) → 虚拟网络编辑器(N)

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,sholor_FFFFFF,t_70)****

 2、由于前面安装Centos7.4时，网络适配器默认选择的是NAT模式，而NAT模式使用的是本机的VMware Network Adapter VMnet8这块网卡，所以这里我们选择VMnet8，再点击"NAT设置"按钮，可以查看到VMnet8 (NAT 模式)下的 子网ip、子网掩码和网关
![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,tecHM6Ly9TM1Mjg3,size_16,color_FFFFFF,t_70)

可以看到我的vmnet8网络下的子网掩码为255.255.255.0 和 网关为 192.168.23.2，所以知道前面为什么要设置为这两个地址了吧，同时可以看到：子网IP 和 网关都同处于 192.168.23这个网段上面，只有最后一位不一致，如果你电脑的 子网IP 和 网关不在同一个网段上，请将网关修改成和子网IP处于同一个网段上，最后一位保持默认即可，即：子网IP最后一位为0，网关最后一位为2 (不过一般默认都处于同一个网段下)

###### **问题二：如何设置我们虚拟机的ip地址，为什么我的 虚拟机ip地址为192.168.23.124**

1、在本地电脑的右下角，右键网络，选择打开“网络和 Internet”设置，进入到如下界面，然后在页面中点击更改适配器选项

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGjg3,size_16,color_FFFFFF,t_70)

2、在页面中找到 VMware Network Adapter VMnet8网卡，并右键选择属性

![img](linux_imag/watermark,type_ZmFuZ3poV0L3FxXzM5MTolor_FFFFFF,t_70)

3、查看 VMware Network Adapter VMnet8网卡的 IPv4地址

![img](linux_imag/watermark,type_ZmFuZ3p1Mjg3,size_16,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmFumV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

可以看到我的 VMnet8下的IPv4 地址为 192.168.23.1，大家有没有发现VMnet8下的IPv4地址与子网IP 和 网关也同处于192.168.23这个网段下，如果VMnet8下的IPv4地址与子网IP 和 网关不同处一个网段下，请修改VMnet8下的IPv4地址与子网IP 和 网关处于同一个网段下，最后一位默认为1即可

前面说了这么多，那我们的虚拟机的IP地址为啥是192.168.23.124呢，因为我们在设置虚拟机的IP地址时，需要保证虚拟机的IP地址 与 VMnet8下的IPv4地址处于同一个网段下，即：前面必须是192.168.23，这样虚拟机才能跟我们的本地电脑互相通信，最后一位数不相同即可，但是最后一位不能设置跟我们的子网IP、网关 和 VMnet8下的IPv4地址相同，即最后一位不能设置为0、2 和 1，例如虚拟机的IP地址可以设置为192.168.23.124 或者 192.168.23.168都是可以的

##### **3、设置DNS地址**   

~~~markdown
1. vi /etc/resolv.conf    //编辑 resolv.conf文件
2. nameserver 114.114.114.114   //添加DNS地址
3. 可以添加多个DNS地址，格式为：
 	nameserver xxx1.xxx1.xxx1.xxx1
	nameserver xxx2.xxx2.xxx2.xxx2
 	常用的DNS地址:阿里  223.5.5.5  或者  223.6.6.6谷歌  8.8.8.8国内移动、电信和联通通用的DNS  114.114.114.114
~~~

![img](linux_imag/watermarzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,sha6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTMFFFF,t_70)

~~~markdown
	提示：如果是内网，配置上面的DNS地址有可能是访问不了外网的，在电脑右下角的网络图标中鼠标右键，选择打开"网络和Internet"设置，选择WLAN，然后在点击你连接			 的网络，查看网络信息


~~~

![img](linux_imag/shadowmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

填写内网的IPv4 DNS 服务器地址即可

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGNzZG4ubmV0Le_16,color_FFFFFF,t_70)

#####  **4、重启网络服务**

~~~markdown
service network restart
~~~

![img](linux_imag/watermark,type_r_FFFFFF,t_7)

##### **5、测试虚拟机 和 本地电脑是否能够ping通**

###### 5.1、本地电脑 ping 虚拟机

打开“命令提示符”窗口，ping 虚拟机的ip地址 192.168.23.124

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,nLmNzZG4ubmV0L3FxXzM5MTMolor_FFFFFF,t_70)

可以看到本地电脑可以ping通虚拟机



###### 5.2、虚拟机 ping 本地电脑

在虚拟机中 ping 本地电脑VMnet8的IPv4地址 192.168.23.1

![img](linux_imag/size_16,color_FF,t_70)

 可以看到虚拟机也可以ping通本地电脑

**提示：如果ping不通本地电脑ip，请检查一下本地电脑的防火墙是否关闭**

##### **6、查看是否能够访问外网**

~~~markdown
	ping -c3 www.baidu.com
~~~

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,LmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

##### **7、永久关闭 firewalld防火墙（centos7默认的防火墙是firewalld防火墙，不是使用iptables，因此需要关闭firewalld服务）**

~~~markdown
	systemctl stop firewalld.service  // 停止firewalld服务
	systemctl disable firewalld.service // 开机禁用firewalld服务
	iptables -L   //列出所有iptables规则
       
~~~

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadoy9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

##### **8、永久关闭SELinux防火墙**

~~~markdown
 	vi /etc/sysconfig/selinux       //编辑selinux文件
 	SELINUX=disabled         //把文件中的SELINUX=enforcing 改成 SELINUX=disabled 即可
 	sestatus    //查看SELinux状态
~~~

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGV6Ly9ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

**获取当前selinux防火墙的安全策略**

~~~markdown
	sestatus
~~~

**可以看到当前selinux防火墙的安全策略仍为enforcing，配置文件并未生效**

![img](linux_imag/watermark,type_ZmFuZ3poZW5nanLmNzZG4ubmV0L3FxFF,t_70)

这时需要我们输入 **重启命令“reboot”**，再去查看SELinux防火墙的状态，可以看到已经关闭了

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

##### **9、给/etc/rc.d/rc.local 文件设置 “x”可执行权限，最初设置默认是没有可执行权限的**

~~~markdown
	chmod +x /etc/rc.d/rc.local     //设置可执行权限
	//设置前
	rwxr-xr--. 1 root root 473 Aug  5  2017 rc.local
	//设置后
	-rwxr-xr-x. 1 root root 473 Aug  5  2017 rc.local
~~~

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_109ibG9nLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

##### **10、输入“halt”关机命令，关闭虚拟机，并拍摄快照，保存当前配置**

![img](linux_imag/size_16,color_FFFFFF,t_70)

![img](linux_imag/watermark,type_ZmFuZ3poZW5naGVpnLmNzZG4ubmV0L3FxXzM5MTM1Mjg3,size_16,color_FFFFFF,t_70)

[超详细的CentOS7.4下载与图文安装](https://blog.csdn.net/qq_39135287/article/details/83993574)

[Linux 下安装与设置Vim编辑器](https://blog.csdn.net/qq_39135287/article/details/84025231)

[CentOS7使用Chrony实现时间同步](https://blog.csdn.net/qq_39135287/article/details/119685229)