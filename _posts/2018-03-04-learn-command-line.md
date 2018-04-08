---
title: "常用command line 归档"
categories:
  - 技术与效率
tags:
  - command-line
---


```
- man
- ls: 列出目录内容
	- ls -l > fileList.txt 利用命令行输出文件名列表的方法
- cd: 前往其他目录 cd..后退一个层级 cd ~退到最初
- pwd: 显示当前目录（也就是工作目录）
- open / start：打开一个文件（分别在 Mac 和 Windows 电脑上）
- touch：创建一个特定扩展名或文件类型的新文件
- mkdir：创建一个新目录
- rm：永久删除一个文件
- rmdir：永久删除一个空目录
- rm -r：永久删除一个目录及其内容（无确认过程，请谨慎使用！)
- rm -ri：永久删除一个目录及其内容（有确认过程)
- Start 打开文件或目录
- 鼠标拖文件夹到命令行界面
- TAB 键自动补齐当前目录下的文件和目录的名称
- Touch 创建文件
- Mkdir 创建文件夹
- Rm 删除文件
- Rmdir 删除目录（不能删除有内容的目录）
- Rm -r
- open .打开所在文件夹
- open ~
- open /home/
- lsof -i :1086 检查端口占用
- tldr    简洁的命令介绍
- curl cip.cc
- curl ip.cn
- vimtutor 调出vim教程
```




注意： 你应该避免在目录名和文件名中使用空格（而是使用下划线如 cloven_hoofed_animals）。如果不可避免 —— 也许遇到以前创建的文件或目录名称中有空格，可以在空格之前插入一个转义字符（\），告诉 shell 如何正确得解释文件名中的空格，比如 mkdir cloven\ hoofed\ animals。