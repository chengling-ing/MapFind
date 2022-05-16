

# MapFind



## 简介

​		适合小白、新手的，以域名作为切入点进行 whois 查询、子域名爆破、端口的轻量化一键式信息收集，代码结构简单可供借鉴学习。

![](image\1.png)



**说明**: 我这里是将源文件打包成了 exe 文件，运行一次程序会在当前目录下以追加方式生成一个'default.log' 作为运行信息记录将屏幕所以输出进行保存，避免杂乱可以运行一次在删除default.log文件后再次运行。另外个人也是新手，需要改进的地方还很多，不足的地方还请指正！！！





## 安装环境

 		工具使用Python3语言开发，在运行之前请确保您装有 'Python3.X' 软件及 'pip3' 软件支持。

##### 安装所需的运行库：

```
pip3 install requirements.txt
```





## 使用方法



显示帮助命令：

```
./MpFind.exe --help
```



扫描单个url:

```
./MpFind.exe --url xbaidu.com             #默认3线程
./MpFind.exe --url xbaidu.com --thread 10 #线程设置10
```



从文档导入url:

```
./MpFind.exe --file file.txt               #默认5线程
./MpFind.exe --file file.txt --thread 20   #线程设置20
```