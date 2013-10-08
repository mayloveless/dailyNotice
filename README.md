dailyNotice
===========
使用node-webkit制作的桌面小应用

主要功能：

1、 显示当时天气

2、 定时提醒

3、 显示当日更新美剧


node-webkit打包方法
==================
1、把程序文件包压缩成zip，并命名为nw

注意：package.json要在root节点，所以就不要压缩文件夹了，就全选压缩就好。

2、copy /b nw.exe+app.nw app.exe 

把app.nw放进nw.exe目录，把nw.exe 压进去

3、用Enigma Virtual Box软件把nw.pak和*.dll压进去

1）选刚压了nw.exe的app.exe

2)点add选择nw.pak和*.dll依赖。基本用default就好，然后ok

3）Press 'File Options', choose 'Compress Files', and 'OK' 

4）Process

4）最后压出来个新exe，就好了

node-webkit教程及文档
======================
https://github.com/rogerwang/node-webkit

http://oklai.name/2013/04/%E8%BF%99%E5%B9%B4%E5%A4%B4%EF%BC%8C%E4%BD%A0%E5%8F%AA%E9%9C%80%E8%A6%81%E6%87%82node-webkit/