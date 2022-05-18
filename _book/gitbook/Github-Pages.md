# 发布到 Github Pages

---

### 1. 申请 Github 账号

***

### 2. 创建一个项目仓库

#### 2.1 新建仓库

<img src="images/GitHub2.png">

#### 2.2 设置仓库信息

<img src="images/GitHub3.png">

#### 2.3 创建完成

<img src="images/GitHub4.png">

***

### 3. 推送静态网站文件到 Github 仓库中

#### 3.1 创建Git

在项目文件夹下进入CMD终端，输入 `git inin` 命令，会创建一个 `.git` 的隐藏文件

#### 3.2 设置 SSH Key

输入命令 `ssh-keygen -t rsa` 回车

<img src="images/GitHub-SSH1.png">

#### 3.3 获取 SSH Key

输入命令 `cat ~/.ssh/id_rsa.pub` ，复制 SSH

<img src="images/GitHub-SSH2.png">

#### 3.4 添加 SSH Key

<img src="images/GitHub-SSH3.png">
<img src="images/GitHub-SSH4.png">
<img src="images/GitHub-SSH5.png">

#### 3.5 连接远程仓库

#### 3.6 创建分支

由于源码文件和静态文件在一个仓库中，所以好的准则将按如下分支：  
>* master, 		保存书籍源码.md文件
>* gh-pages, 	保存书籍编译后的 HTML 文件，即_book/

***

### 4. 创建 Pages 服务并部署自己的静态网站

***

### 5. Pages 配置

***