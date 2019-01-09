# Tools_for_trainee
一个编程菜鸟的日记

很久以前就意识到自己材资平庸。2019年伊始，想记录一些东西，这样2020年的时候，可以看见自己经过的轨迹。
近两年来，程序员群体似乎突然受到了大家的重视。 有关程序员的穿衣，秃头，熬夜，Debug，相亲段子随处可见。
我所认识的优秀的程序员，大多偏执。他们经手的PPT、代码、报告， 容不得马虎和凑合，追求极致的简洁。
所以，**Markdone**、**JupyterNotebook**、**Sublime** 这样的工具得到了他们的青睐。想融入他们，先要有“统一的语言”，那就从这些工具开始吧。

## Markdone 常用命令
```
# 后加一个空格，是最标准的Markdown语法。
> 是引用
- 是无序列表
*倾斜*
**加粗**
`这是一行代码`

|表格1|表格2|表格3|
|--|--|--|
|内容1|内容2|内容3|

```
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

## Jupyter Notebook 常用命令
- 命令行里先进入文件`cd /usr/project0/code`
- 然后打开jupyter notebook `jupyter notebook`
- 逐cell执行python命令

快捷键有 

- Ctrl-Enter : 运行本单元
- Alt-Enter : 运行本单元，在其下插入新单元


## 服务器常用命令
本地是Linux系统时，链接服务器`ssh username@ip`
- 在服务器上创建自己的程序窗口 `screen -S your_program_name`
- 退出窗口`Ctrl+a+D`
- 链接已创建的窗口 `screen -r your_program_name `
- 查看有哪些窗口存在 `screen -ls`
- 查看GPU使用情况 `nvidia-smi`

## Linux 常用命令
- pwd 显示工作路径 
- ls 查看目录中的文件 
- rm -rf dir1 删除一个叫做 'dir1' 的目录
- cp -r dir1 dir2 复制dir1内容到dir2
- whereis halt 显示一个二进制文件、源码或man的位置 
- which halt 显示一个二进制文件或可执行文件的完整路径
- du -sh dir1 估算目录 'dir1' 已经使用的磁盘空间
- mount /dev/cdrom /mnt/cdrom 挂载一个cdrom或dvdrom 
- zip -r file1.zip file1 file2 dir1 将几个文件和目录同时压缩成一个zip格式的压缩包 
- unzip file1.zip 解压一个zip格式压缩包

## Sublime 常用命令
- Ctrl+Enter 在下一行插入新行
- Ctrl+Shift+D 复制光标所在整行，插入到下一行
- Ctrl+/ 注释单行。
- Ctrl+Shift+/ 注释多行
