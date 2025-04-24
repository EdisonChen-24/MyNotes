# To GotHub
1.基本配置
>git config --global user.name "你的用户名"
>git config --global user.email "你的邮箱"

2.初始化仓库
>git init

3.查看当前状态
>git status

4.添加文件到暂存区
* 添加单个文件
>git add 文件名

* 添加所有文件
>git add *

5.提交更改
>git commit -m "描述"

6.查看提交历史
>git log

7.克隆远程仓库
从远程仓库（如 GitHub）克隆一个项目，可以使用 git clone 命令：
>git clone 仓库地址

8.查看远程仓库
使用 git remote 查看当前 Git 仓库连接的远程仓库：
>git remote -v

9.拉取远程仓库的更改
从远程仓库获取最新的更改，可以使用 git pull：
>git pull origin main

10.推送更改到远程仓库
完成本地修改并提交后，使用 git push 将更改推送到远程仓库：
>git push origin main

11.推送到GitHub
>git remote add origin https://github.com/EdisonChen-24/MyNotes.git
>git push -u origin master
