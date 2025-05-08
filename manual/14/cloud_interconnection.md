### 云端互联
Hi168平台为了让云端虚拟机和本地环境彻底打通，建立一个VPN虚拟通道，方便用户在本地可以通过SSH等工具直接连接上云端的虚拟机，省去本地安装虚拟机的繁琐过程，推出了云端互联这个重磅功能，特点包括：

**<li>本地与云端无缝集成</li>**

**<li>ping通云端虚拟机</li>**

**<li>本地无需安装虚拟机</li>**

**<li>低配置使用高端集群</li>**

![alt text](../help_picture/14_desktopcentor17.png)

![alt text](../help_picture/14_desktopcentor18.png)

![alt text](../help_picture/14_desktopcentor19.png)

#### 云端互联不通的解决方式：
##### 1、关闭重新开启
![alt text](../help_picture/14_desktopcentor20.png)
##### 2、删除重新创建（若步骤1无效）
![alt text](../help_picture/14_desktopcentor21.png)

![alt text](../help_picture/14_desktopcentor22.png)
##### 3、任务管理器杀掉相关进程（若步骤2也无效）
<li>先按步骤1和2关闭删除，然后在本地计算机启动任务管理器找到对应的进程将其杀掉。</li>

![alt text](../help_picture/14_desktopcentor23.png)
<li>然后重新创建启动</li>

#### 下载互联工具（可选方式，针对较专业人士使用）
##### 1、官网下载WireGuard
![alt text](../help_picture/14_desktopcentor24.png)

![alt text](../help_picture/14_desktopcentor25.png)
##### 2、安装使用
（1）点击“详情”按钮，再点击“下载云端互联配置文件”将VPN配置文件下载到本地。

![alt text](../help_picture/14_desktopcentor26.png)

![alt text](../help_picture/14_desktopcentor27.png)

（2）双击下载好的安装包“wireguard-installer.exe”，它将自动完成安装。

![alt text](../help_picture/14_desktopcentor28.png)

（3）打开WireGuard软件，点击“从文件导入隧道”。

![alt text](../help_picture/14_desktopcentor29.png)

（4）选择下载好的配置文件，点击“打开”。

![alt text](../help_picture/14_desktopcentor30.png)

（5）再点击“连接”，状态将变为“已连接”。

![alt text](../help_picture/14_desktopcentor31.png)

![alt text](../help_picture/14_desktopcentor32.png)

这样与云端就建立好了VPN隧道，可以进行云端互联了。