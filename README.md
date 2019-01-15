# flask-tutorial
###### 参考网址：教程 — Flask 1.0.2 documentation
https://dormousehole.readthedocs.io/en/latest/tutorial/index.html
#### 介绍
本网站是参照如上网址写的一个flask demo。




#### 运行环境：
###### 如下是经测试的运行环境
‘’‘
root@iZwz949xsbbksi0oz7skz0Z:~# conda -V
conda 4.5.11
root@iZwz949xsbbksi0oz7skz0Z:~# python
Python 3.6.5 |Anaconda, Inc.| (default, Apr 29 2018, 16:14:56) 
[GCC 7.2.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 

’‘’
#### 使用说明：

1. 初始化数据库：
'''
root@iZwz949xsbbksi0oz7skz0Z:~/code_test/-flask-tutorial# flask init-db
Initialized the database.
'''
2. 运行如下代码：
'''
root@iZwz949xsbbksi0oz7skz0Z:~/code_test/-flask-tutorial# export FLASK_APP=flaskr
root@iZwz949xsbbksi0oz7skz0Z:~/code_test/-flask-tutorial# export FLASK_ENV=development
root@iZwz949xsbbksi0oz7skz0Z:~/code_test/-flask-tutorial# flask run -h 0.0.0.0 -p 80
'''
3. 打开一个浏览器（可以不是同一个网络），输入：120.78.85.216:80
