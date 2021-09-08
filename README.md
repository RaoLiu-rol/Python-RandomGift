# Python抽奖小程序
Lottery program with Tkinter

#### 介绍 / Introduction
Python抽奖小程序，从excel中获取待抽奖人员名单，并根据Tkinter上输入的抽奖人数进行滚动抽奖
A small lottery program by using Tkinter and Openpyxl, get list of candidates to be drawn from .xlsx in 2nd column, start lottery when you type in the amount you need and press start button, the name list will start rolling, and when you press confirm button, show the lucky one's name in label.

#### 软件架构
软件架构说明


#### 安装教程

1.  确保在python库中安装了openpyxl库
    pip install openpyxl
2.  在Excel中录入待抽奖人员名单，可以只录入姓名列
    type in the list of candidates to be drawn to the peopleList.xlsx's 2nd column
3.  运行py文件，输入待抽奖人数，点击开始，开始滚动，点击确定，停止滚动
    run randGift.py, type in the amount you need to lottery, and press left button for start rolling, press right button to stop

![image](https://user-images.githubusercontent.com/53886433/132345513-6d7648c0-6c41-461f-8c0c-7c290803829b.png)
