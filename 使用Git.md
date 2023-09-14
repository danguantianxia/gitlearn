## 使用Git

### 1. 推送变更

![img](https://www.runoob.com/wp-content/uploads/2014/05/trees.png)

1.1 提出更改，添加到Index区

​	`git add *`

1.2 .提交改动到HEAD区

​	`git commit -m "提交备注"`

1.3 .推送改动到仓库

​	`git push origin master`



### 2. 分支

2.1 创建分支

​	git checkout -b 分支名

2.2 切换分支

​	git checkout 分支名

2.3 删除分支

​	git branch -d 分支名

2.4 推送分支

​	git push origin <branch>