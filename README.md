# 项目使用须知
* 项目内部使用了 YOLOv11 进行目标检测，所以使用前需要配置YOLO环境
* YOLO全系列环境配置参照[YOLO全家桶配置](https://blog.csdn.net/qq_51977316/article/details/143487111)
* 运行过程中会在项目目录中创建文件夹
* 项目内调用py脚本的类文件调用的是项目内部的 Python 解释器，使用时需要更改 PythonCaller.java 的变量
