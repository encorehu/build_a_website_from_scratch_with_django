# 添加官方网站的投票应用

## 使用命令创建一个app: poll

在mysite项目(包含manage.py的那个目录)下, 执行命令:

    manage.py startapp poll

命令的解释:

    manage.py 这个是你的当前项目用到的一个通用的命令文件, 里面包含了很多的命令, 具体的以后慢慢会接触到.

    startapp 是上面的命令文件中的一个命令, 他的作用是为你当前的项目创建一个可以重用的app(意思是可以用到别的项目中去), 他的参数就是后面的poll

    poll 这个是startapp的参数, 也就是app name

这个命令执行完之后, 在mysite项目下, 就会出现一个文件夹, 名字就是poll
