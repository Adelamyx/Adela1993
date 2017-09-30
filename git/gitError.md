# git常见错误的修改

## 参考[git教程-廖雪峰](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

## 目录
* 1.[给已经存在的项目添加Git](#1)
* 2.[git查看当前路径所属manifest中的哪个project 有两个命令](#2)

## 正文

### 1 ###
### 给已经存在的项目添加Git
### [coder-温群香的博客](http://blog.sina.com.cn/s/blog_13170e2500102wgjp.html)
**本地存在.git删除并重新添加新的.git**
```
1、打开终端​，输入以下命令来到你的项目：
  cd /Users/QunXiang Wen/Desktop/GitDemo
2、输入以下命令行，初始化一个本地仓库：
  ​git init
3、输入以下命令，把工程所有文件都添加到该仓库中（千万别忘记后面的.号！！！）：
  ​git add .
4、输入以下命令，把文件提交到本地仓库：
  git commit -m "Initial commit"​
  如果出现nothing to commit, working directory clean​说明你已经提交好了。
5、输入以下命令，添加远程仓库地址：
  输入：git remote add origin + 你的仓库地址
  例如：git remote add origin https://git.oschina.net/hhh/GitDemo​.git
  如果出现fatal: remote origin already exists.​说明你已经添加过远程仓库了，
  输入以下命令删除远程仓库：git remote rm origin，然后再次执行第5步。
6、​输入以下命令，把文件提交到远程仓库：
  git push -u origin master​
  然后你就等着它提交完成就完事了。
```
### 2 ###
### git查看当前路径所属manifest中的哪个project有两个命令
### [rockly89的博客](http://blog.csdn.net/ly890700/article/details/52709255)
```
1 git config -l  
2 git remote -v
➜  test123 git:(master) git remote -v
origin	git@github.com:Adelamyx/test123.git (fetch)
origin	git@github.com:Adelamyx/test123.git (push)
```
