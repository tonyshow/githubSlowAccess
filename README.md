# githubSlowAccess
github访问慢问题解决

打开终端，编辑hosts文件
sudo vim /etc/hosts

# Github
添加以下内容
151.101.185.194 github.global.ssl.fastly.net
192.30.253.112 github.com 
151.101.112.133 assets-cdn.github.com 
151.101.184.133 assets-cdn.github.com 
185.199.108.153 documentcloud.github.com 
192.30.253.118 gist.github.com
185.199.108.153 help.github.com 
192.30.253.120 nodeload.github.com 
151.101.112.133 raw.github.com 
23.21.63.56 status.github.com 
192.30.253.1668 training.github.com 
192.30.253.112 www.github.com 
151.101.13.194 github.global.ssl.fastly.net 
151.101.12.133 avatars0.githubusercontent.com 
151.101.112.133 avatars1.githubusercontent.com
刷新dns
dscacheutil -flushcache
