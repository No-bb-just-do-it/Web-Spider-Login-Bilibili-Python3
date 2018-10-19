# Web-Spider-login-bilibili-python3
## 网络爬虫模拟登陆bilibili-滑动验证码的破解-更新至version14.py-2018-10-9
## version14： 可自动发送弹幕
### 思路：
###  1.先从网站上找到验证码，并完成拼接
#### 原始图像：
- 1
![](1bg.png)
- 2
![](2bg.png)
#### 拼接好后的滑动验证码：
- 1
![](fullbg.jpg)
- 2
![](gapbg.jpg)
### 2.比较两图片，找到缺口的左侧边界，误差阈值为60是比较合适的
### 3.按先加速再减速的方式拖动验证码，加速度，中间位置需调整好
### 4.运行程序，登陆成功！
## 注意：
### 请先安装chrome和chromedriver以及bs4,selenium库
#### 捕获的信息:
![](keys.jpg)
