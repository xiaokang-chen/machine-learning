# M1 MAC安装机器学习环境遇到问题汇总

1. 虚拟环境无法安装matplotlib
报错关键信息：
```
The headers or library files could 
not be found for jpeg
```

MAC缺少jpeg库：
```
$ apt list | grep jpeg*.dev
$ sudo apt install libjpeg-dev libopenjpeg-dev
```
参考：https://www.pynote.net/archives/2417

2.