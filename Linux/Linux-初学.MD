# 初始化相关配置

[Linux下载地址](https://ubuntu.com/#download)

1. 安装toools：用于VMware和ubuntu之间移动鼠标

2. 安装VNware：虚拟机软件。

3. 创建普通用户权限，不要用root权限直接登录.

4. 安装gnome界面（可以选择不安装）

5. 网络配置DNS和安装vim/man

## 部分基础命令

更新软件和软件源

```c
sudo apt-get install update
sudo apt-get install xxx
sudo apr-get remove xxx
```

VIm插件   ctag(设立标签--为跳转提供基础)和Taglist(罗列关键词)
ctag 光标放在关键字用"Ctrl+]"跳转到函数  Ctrl+O返回
man帮助命令  
mkdir name创建文件夹
man -f read 查询命令用法

### 快捷命令

```c
date        //显示当前时间
df          //显示剩余磁盘
touch apple //创建名为apple的文件
mkdir apple //创建名为apple的文件件
ls          //显示当先文件夹下的目录
ls -a       //隐藏目录
man -f      //帮助命令
tree xxx    //显示当前文件路径
file filename//描述文件类型
```

Ubuntu 设置Tab缩进：

```c
su root
vi /etc/vim/vimrc
set ts=4
```

### gcc编译

```c
gcc hello.c -o hello//将.c文件编译成名字为hello的.out文件
gcc hello.c -o hello.i -E//预处理.i文本 
gcc hello.i -o hello.s -S//编译截至
gcc hello.s -o hello.o -c//汇编截至
gcc hello.o -o hello -lc -lgcc//链接截至
./hello //运行hello.out文件
```

### vim

```c
:%s/sb/SB/g    //全局替换变量 将“sb”改成“SB”

```