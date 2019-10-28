# upgradeOpenSSH
一键升级CentOS 7上的OpenSSH到8.1p1
## 使用方法
```
./upgradeOpenSSH
```
## 脚本运行完后
```
source /etc/profile.d/path.sh
或者重新开一个新的ssh连接
然后即可检查ssh是否升级成功
ssh -V
```

### OpenSSH地址
`https://openbsd.hk/pub/OpenBSD/OpenSSH/portable/`
### OpenSSL地址
`https://ftp.openssl.org/source/`