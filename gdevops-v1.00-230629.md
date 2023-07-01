# git

## 安装

在Mac OS X上安装Git

一是安装homebrew，然后通过homebrew安装Git，具体方法请参考homebrew的文档：http://brew.sh/。

第二种方法更简单，也是推荐的方法，就是直接从AppStore安装Xcode，Xcode集成了Git，不过默认没有安装，你需要运行Xcode，选择菜单“Xcode”->“Preferences”，在弹出窗口中找到“Downloads”，选择“Command Line Tools”，点“Install”就可以完成安装了。



## 相关命令

### 创建版本库

版本库又名仓库，英文名repository，你可以简单理解成一个目录，这个目录里面的所有文件都可以被Git管理起来，每个文件的修改、删除，Git都能跟踪，以便任何时刻都可以追踪历史，或者在将来某个时刻可以“还原”。

所以，创建一个版本库非常简单，首先，选择一个合适的地方，创建一个空目录：

````
$ mkdir learngit
$ cd learngit
$ pwd
/Users/michael/learngit
````

第二步，通过git init命令把这个目录变成Git可以管理的仓库：
````
$ git init
Initialized empty Git repository in /Users/michael/learngit/.git/
````
### 添加文件到库中

使用命令git add <file>，注意，可反复多次使用，添加多个文件；
使用命令git commit -m <message>，完成。

### 查看状态、变化等

要随时掌握工作区的状态，使用git status命令。

如果git status告诉你有文件被修改过，用git diff <file> 可以查看修改内容。

穿梭前，用git log可以查看提交历史，以便确定要回退到哪个版本。
git log --pretty=oneline

要重返未来，用git reflog查看命令历史，以便确定要回到未来的哪个版本。

- git config
  //暂时似乎用不到

---

# Python

## 安装 python3

1、访问https://www.python.org/downloads/macos/
2、选择Python 3.11.4 - June 6, 2023 | Download macOS 64-bit universal2 installer
3、在Mac运行 installer，按界面提示做操作

在terminal运行：
1、python3
george1442@192 ~ % python3
Python 3.9.6 (default, May  7 2023, 23:32:45) 
[Clang 14.0.3 (clang-1403.0.22.14.1)] on darwin
Type "help", "copyright", "credits" or "license" for more information.

2、运行python3.11
george1442@192 ~ % python3.11
Python 3.11.4 (v3.11.4:d2340ef257, Jun  6 2023, 19:15:51) [Clang 13.0.0 (clang-1300.0.29.30)] on darwin
Type "help", "copyright", "credits" or "license" for more information.

# ruby

---


