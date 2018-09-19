# ProxyTools

## 1.plink.exe

### 介绍

plink可以在ssh隧道中进行代理，无需安装其他软件，只要目标服务器开启SSH即可。

### 用法

plink.exe -C -N -D 127.0.0.1:1080 username@ip -pw passowrd
