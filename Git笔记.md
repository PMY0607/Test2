## Git笔记

### git相关概念

工作区：就是你电脑上敲代码的原文件

缓冲区：临时保存提交的改动

本地仓库：敲好代码后，放到本地仓库后，准备放到远程仓库

远程仓库：网络给你托管的仓库

 ![image-20220225164015106](/Users/pengmingyuan/Library/Application Support/typora-user-images/image-20220225164015106.png)



### git常用命令

1. 仓库地址操作

​	git remote add origin <远程仓库地址>：本地仓库和远程仓库关联

​	git remote rm  origin <远程仓库地址>：删除远程仓库地址

​	git remote add origin <远程仓库地址>：添加远程仓库地址

​	git remote set-url origin  <远程仓库地址>：修改远程仓库地址

2. 分支操作

​	git branch：查看所有分支

​	git checkout：切换分支

​	git branch 《分支名》：新建分支

​	git checkout -b  <a名>：新建分支并切换到新建的分支

3. 提交操作

​	git add . ：将当前项目文件加入到缓冲区

​	git commit -m "注释"：将上传的文件添加注释

​	git push origin master：推送最新更改

4. 拉取操作

​	git fetch origin 《远程分支名》：拉取远程仓库的分支代码带缓冲区

git pull 《远程主机名》 《远程分支名》：拉取远程制定分支的更新并直接合并
