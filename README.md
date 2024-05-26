# toursim-assistant    
在本地启动mysql和redis
mysql地址默认127.0.0.1:3306
redis地址默认127.0.0.1:6379
在main/views.py设置api

set FLASK_APP=app.py
flask db init
flask db migrate
flask run
