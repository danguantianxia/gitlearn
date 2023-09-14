# gitlearn
用来学习github的学习仓库

1.本地安装git程序后，通过ssh-keygen命令生成密钥

​	`$ ssh-keygen -t ed25519 -C "邮箱"`

生成过程中可输入密钥的生成路径和密码。

2.进入~/.ssh/目录下，查看并复制.pub文件中的密钥内容。

3.配置添加至ssh

​	`eval “(ssh-agent -s)”`

​	`ssh-add ~/.ssh/密钥文件名`

4.登录GitHub，在setting中添加ssh keys，title随意填写，但key type必须选择“Authentication Key”。

5.验证

​	`ssh -T git@github.com`

6.克隆项目到本地

​	git clone git@github:"GIT用户名"/“GIT项目名”.git
