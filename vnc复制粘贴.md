# vncviewer连接Ubuntu16.4不能进行双向的复制粘贴  
**如果Vnc Viewer不能复制黏贴，输入一下命令(需要在打开的vnc界面及对应的用户下执行)：**  
> vncconfig -nowin&  

查看命令是否执行成功  
> siji32@mtf-lane-test:~$ ps -ef | grep vncconfig  
siji32    74937  94574  0 03:17 pts/22   00:00:00 vncconfig -nowin

**在VNC Viewer界面设置开启允许输入**
![](https://github.com/crl608/123/blob/master/vnc粘贴配置.png)
