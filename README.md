创建虚拟环境：
1. [virtualenv ](https://dormousehole.readthedocs.io/en/latest/installation.html#install-create-env)
- windows
```
py -3 -m venv venv
```
- 激活虚拟环境
```
venv\Scripts\activate
```
- 安装 Flask
```
pip install Flask
```
2. 搭建好项目布局后，windows下 启动flask
```
venv\Scripts\activate

set FLASK_APP=flaskr

set FLASK_ENV=development

flask run
```
3. 浏览器访问，http://127.0.0.1:5000/auth/login