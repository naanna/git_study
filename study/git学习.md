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
1. 上传文件
	1. `git status`
	1. `git add xxx`
	1. `git commit -m "xxxx"`
	1. `git push`
1. 下载文件
	1. `git pull`
1. 克隆项目
	1. `git clone xxxxx`
## Android studio 上传
1. `git init`
1. `git add .`
1. `git commit -m “commit info”`
1. `git remote add origin git@github.com:naanna/xxx.git`(若要移除可先输入`git remote rm origin` )
1. `git push origin master` (若出错则说明没有同步可先输入`git pull origin master`)
