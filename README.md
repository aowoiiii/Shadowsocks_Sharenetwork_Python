### 利用Shadowsocks搭建校园网共享 v2
	
可用于Windows的shadowsocks服务端搭建  
基于Python + OpenSSL  理论上更稳定  

##### 1.安装Python (项目附带python-3.4.3.amd64.msi)  
```
各种下一步(Next)安装，默认安装目录 C:\Python34(下面环境变量将按照此目录)  
    设置环境变量:  
        在Path添加以下两项:(win7系统请注意用 ; 隔开)  
	    C:\Python34  
	    C:\Python34\Scripts   
tip:环境变量设置成功后 在CMD输入python 会有版本显示  
```
##### 2.安装OpenSSL (项目附带Win64OpenSSL-1_0_2o.exe)  
	无脑下一步(Next)直接安装  
##### 3.安装Shadowsocks  
	打开CMD 输入pip install shadowsocks  
##### 4.启动Server_Start.bat  
相关配置文件参考之前 [Shadowsocks_sharenetwork](https://github.com/aowoiiii/Shadowsocks_sharenetwork)
