# VS Code 运行 Gitbook

---

### 打开终端

<img src="images/zhongduan1.png">

***

### 初始化配置

1.在vscode终端里输入npm init，然后一直空格直到出现完yes

<img src="images/zhongduan2.png">

成功后出现以下这个json文件

<img src="images/zhongduan3.png">

2.更改文件代码并保存

{
  "name": "vswebdesgin",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "serve": "gitbook serve",
    "build": "gitbook build"
  },
  "author": "",
  "license": "ISC"
}

<img src="images/zhongduan4.png">

3.运行服务

npm run serve

<img src="images/zhongduan5.png">