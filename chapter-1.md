Django建站基础知识吧.

Django的下载和安装

1.Django的下载
这个当然是到django的官方网站去下载了, 地址是 http://www.djangoproject.com/ 
打开之后, 点击 download, 或者点击找到最新版本就可以点击下载了.

2. Django的安装
因为Django是一个python web开发框架, 所以安装django还需要实现装好python, 这里我假设你以前都没有学过python, 因为这里就是讲的要从零开始学习django的.
那么现在要做的事情就是, 再下载一个python的安装包. 到http://www.python.org/ 下载python3.3的msi安装包.

下载完成后, 可以开始了
1. 安装python3.3, 一路下一步, 直到结束.
2. 桌面上右键点击'我的电脑', 选择'属性', 
3. 然后在弹出的属性对话框中点击'环境变量', 在用户变量中选择path, 双击或者点击编辑按钮, 在最末尾加上';C:\Python3;C:\Python3\Scripts'
4. 按win+R 打开运行对话框, 输入cmd, 打开windows下的命令行, 输入python命令, 如果执行成功, 说明python装好了.
5. 下面就可以开始装django了. 解压缩下载回来的django-1.5.tar.gz文件(使用winrar既可解压, 7zip应该也行)
6. 进入解压后的目录, 在命令行下执行 setup.py install, 一大堆字符狂飙之后, 就安装好了.

Django的Hello World
django装好了, 就可以开工了.
到你的D盘, 创建一个目录, 叫做Projects, 以后所有的项目都在这个目录下进行.

使用命令行进入D:\Projects\, 执行命令: django-admin.py startproject mysite
可以看到D:\Projects\ 目录下自动生成了一个 mysite目录. 

命令行下进入这个 mysite 目录, 执行命令 manage.py runserver, 如果出现以下字符, 则表示这个django项目使用django自带的调试用web服务器已经运行在本机8000端口了:


打开 你喜欢的网页浏览器, 输入 http://localhost:8000/ 你就可以看到以下内容:


如图:

则表示, 你已经成功的创建 一个django的hello world项目了