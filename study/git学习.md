# GIT学习

## 配置本地环境

1. [github网址](https://github.com/)
1. [git下载](https://git-scm.com/download/win)
1. 配置git和github
	1. `ssh -T git@github.com`（检测是否能连接到github）
	1. `ssh-keygen -t rsa -C "your_email"`（创建本地SSH Key）
	1. `cat ~/.ssh/id_rsa.pub`（cat public key）
	1. github上传public key
	1. `ssh -T git@github.com`（测试密钥是否成功）
1. 配置全局设置用户名邮箱配置
	1. `git config --global user.name "nameVal"`
	1. `git config --global user.email "eamil@qq.com"`
	1. `git config user.name/email`
 