(myenv) em2a@em2a-Latitude-E6430:~/Desktop/project/Res_1/06-Login-Auth/Flask_Blog$ python3 run.py
Traceback (most recent call last):
  File "/home/em2a/Desktop/project/Res_1/06-Login-Auth/Flask_Blog/run.py", line 1, in <module>
    from flaskblog import app
  File "/home/em2a/Desktop/project/Res_1/06-Login-Auth/Flask_Blog/flaskblog/__init__.py", line 4, in <module>
    from flask_login import LoginManager
  File "/home/em2a/.local/lib/python3.10/site-packages/flask_login/__init__.py", line 12, in <module>
    from .login_manager import LoginManager
  File "/home/em2a/.local/lib/python3.10/site-packages/flask_login/login_manager.py", line 33, in <module>
    from .utils import _create_identifier
  File "/home/em2a/.local/lib/python3.10/site-packages/flask_login/utils.py", line 14, in <module>
    from werkzeug.urls import url_decode
ImportError: cannot import name 'url_decode' from 'werkzeug.urls' (/home/em2a/.local/lib/python3.10/site-packages/werkzeug/urls.py)
