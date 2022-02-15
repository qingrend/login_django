#用户登录注册系统项目
django3.2 python3.9

##安装
使用pip安装： pip install -Ur requirements.txt
##配置
将example_settings改成settings，将邮箱设置成自己的即可
##数据库
该项目使用django默认的sqlite数据库
python manage.py makemigrations 生成数据库配置文件
python manage.py migrate 数据库迁移

##创建超级用户
Python manage.py createsuperuse
输入用户名，密码，邮箱。超级用户的密码不能过于简单，否则无法通过
用户名密码即后台admin登录的账号和密码

##运行
python manage.py runserver

