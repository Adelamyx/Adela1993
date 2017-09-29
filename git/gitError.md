# git常见错误的修改

## 参考[git教程-廖雪峰](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

## 目录
* 1.[给已经存在的项目添加Git](#给已经存在的项目添加Git)
* 2.[git查看当前路径所属manifest中的哪个project 有两个命令](#git查看当前路径所属manifest中的哪个project 有两个命令)

## 正文

### 给已经存在的项目添加Git ###
**本地存在.git删除并重新添加新的.git**
```
查看本地
```

### git查看当前路径所属manifest中的哪个project有两个命令 ###
### [rockly89的博客](http://blog.csdn.net/ly890700/article/details/52709255)
```
1 git config -l  
2 git remote -v
➜  test123 git:(master) git remote -v
origin	git@github.com:Adelamyx/test123.git (fetch)
origin	git@github.com:Adelamyx/test123.git (push)
```
