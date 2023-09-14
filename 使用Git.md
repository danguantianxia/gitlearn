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

​	`git checkout -b 分支名`

2.2 切换分支

​	`git checkout 分支名`

2.3 删除分支

​	`git branch -d 分支名`

2.4 推送分支

​	`git push origin 分支名`



### 3. 更新与合并

3.1 更新改动至本地仓库

​	`git pull`

3.2 获取并合并远端的改动到本地

​	`git merge 分支名`

两种方式都可以合并改动，但可能失败甚至出现冲突（conflicts），这种情况下需要手动合并处理，处理完成后需要执行命令标记。

3.3 标记合并

​	`git add 文件名`

3.4 预览差异

​	`git diff 源分支 目标分支`



### 4. 标签

