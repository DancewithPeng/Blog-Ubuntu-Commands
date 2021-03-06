# Blog-Ubuntu-Commands
Ubuntu常用命令

- [curl](#1)
- [netstat](#2)
- [ps](#3)
- [kill](#4)
- [grep](#5)

## curl - URL工具
```bash
  curl [options...] <url>
```
常用的option有

  - `-o 将下载的数据保存到指定的文件`
  - `-i 同时显示HTTP Header`

## netstat - 查看网络状态
```bash
  netstat [options...]
```
常用的option有
  - `-r 显示路由表`
  - `-a 显示所有的socket`
  - `-p 显示PID和程序名称`
  
## ps - 查看进程信息
```bash
  ps [options...]
```
常用的option有 
  - `-e, -A 显示所有进程`
  - `-f 显示全部格式，包括调用的命令`

## kill - 杀死进程
```bash
  kill [signal] <PID>
```
常用的signal有
  - `-9 exit 退出进程`
  
## grep - 全局搜索工具
```bash
  <command> | grep [options...] <RE>
```
常见的option有

  - `-i 忽略大小写`

## cat - 查看文件内容
```bash
  cat [options...] <filename>
```
常见的option有

  - `-a 显示所有内容`
  - `-n 同时显示行号`
  
## tail - 查看文件最末尾的内容
```bash
  tail [options...] <filename>
```
常见的option有

  - `-n 显示最后几行的内容`
  - `-f 显示最后10行内容，并且有新内容增加的时候，自动显示新增的内容`
