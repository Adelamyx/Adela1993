## git 命令

## 命令行
Mac OS 用户，使用 Terminal 或者 iTerm

Windows 用户，使用 git bash

## Mac OS 升级 git

``` bash
git --version

which git -> /usr/local/bin/git

brew unlink git

brew install git

git --version

brew link git

git --version
```

## 初次运行前的配置

### 列出配置项

git config --list

### 修改或增加配置

``` bash
git config --global user.name Adelamyx
git config --global user.email 1084221885@qq.com
```
# 获取帮助

``` bash
git --help

git help x
```
