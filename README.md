# 说明 #
- 初始化 开启服务

        python manage.py migrate
        python manage.py runserver
	

	默认http://127.0.0.1:8000
   

- 安装mysqlclient

        pip install mysqlclient

- model

	  1. 创建models.py文件 定义model 
	  2. 在settings.py 中 INSTALLED_APPS 添加 'mysite' 应用
	  3. python manage.py makemigrations mysite
	  4. python manage.py migrate
    
    
    
