# linux_git
云计算练习仓库
使用 SSH 测试连接

Linux机器中,将生成的公钥在github中进行设置；

/etc/hosts文件中设置，做代理用
140.82.113.4 github.com 
140.82.114.4 gist.github.com

# 添加一下远程仓库地址
git remote add origin github仓库地址
# 查看远程仓库信息
git remote -v
# 将信息提交到远程仓库
# master 表示本地仓库的分支
git push origin master
# 可以在远程仓库和本地仓库都添加一个新的同名分支dev，使用一下命令即可将信息，提交到远程仓库的dev分支中
git push origin dev


