### 默认方式
开启云端互联默认会启动一个WireGuard的VPN服务，帮助用户在本地和云端建立一个虚拟的VPN隧道。

<li>两种方式进入云端互联</li>

![alt text](./cloudinterconnection01.png)

<li>打开云端互联开关（默认已开启）</li>

![alt text](./cloudinterconnection02.png)

<li>获取云端虚拟机ip（也可以通过服务端口中的网络信息获取），打开本地的命令终端（搜索框输入cmd后打开命令提示符），ping一下云端虚拟机的ip，是否互通。</li>

![alt text](./cloudinterconnection03.png)

#### <font color='red'>云端互联不通的解决方式：</font>
##### 1、关闭重新开启
![alt text](./cloudinterconnection04.png)
##### 2、删除重新创建（若步骤1无效）
![alt text](./cloudinterconnection05.png)

![alt text](./cloudinterconnection06.png)
##### 3、任务管理器杀掉相关进程（若步骤2也无效）
<li>先按步骤1和2关闭删除，然后在本地计算机启动任务管理器找到对应的进程将其杀掉。</li>

![alt text](./cloudinterconnection07.png)
<li>然后重新创建启动</li>