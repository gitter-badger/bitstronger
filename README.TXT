﻿1、简介

　　“理治棋壮”（BitStronger）是一个基于中国象棋通用引擎协议（UCCI）的中国象棋计算机博弈引擎。项目采用C++开发，遵循GPL许可，目前版本可运行于32位Windows平台。本引擎通过标准输入和标准输出与支持UCCI的中国象棋界面软件通讯，可实现跨平台及联网的人机、机机对战。

　　详细的使用说明与程序开发文档参见随程序一同发布的docs目录下的文件。

2、版权声明

　　北京理工大学“理治棋壮”中国象棋计算机博弈引擎开发小组版权所有（2006.7～）

　　项目主管：　林　健（北京理工大学计算机科学技术学院）
　　指导教师：　黄　鸿（北京理工大学信息科学技术学院自动控制系系统工程研究所）
　　技术顾问：　赵陈翔（北京理工大学软件学院）
　　开发人员：　林　健（北京理工大学计算机科学技术学院）
　　　　　　　　高　然（北京理工大学计算机科学技术学院）
　　　　　　　　应张彬（北京理工大学软件学院）
　　　　　　　　武　斌（北京理工大学软件学院）

　　联系方式：　lj [at] linjian.org（林健）
　　　　　　　　honghuang [at] bit.edu.cn（黄鸿）

3、第三方版权声明

　　（1）UCCI通信模块ucci.h、ucci.cpp及utility文件夹下的UCCI辅助文件源自ElephantEye 1.4a。作者：黄晨（webmaster [at] elephantbase.net）。黄晨版权所有。

　　（2）开局库文件OpenBook.bin是我们将ElephantEye 1.4a中附带的文本格式开局库文件BOOK.DAT转化为二进制格式并加以筛选得到。作者：黄晨。开局数据是从他的个人网站——《象棋百科全书》（http://www.elephantbase.net）上收录的8000多局对局中整理出来的。

　　（3）头文件evaluation.h中的子力位置评估表修改自ElephantEye 1.4a相关源代码。作者：黄晨。他的子力位置评估表是在参照“梦入神蛋”程序（作者：魏泽人，http://ki11egg.sourceforge.net）的基础上修改得到。

4、网络资源

　　项目主页：　https://github.com/sswv/bitstronger
　　项目 Git：　git@github.com:sswv/bitstronger.git
　　主管BLOG：　http://blog.linjian.org
