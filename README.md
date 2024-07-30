# 프로젝트 구조
```
myproject/ # 프로젝트 - 프로젝트 실행에 필요한 메인 모듈
    manage.py
    myproject/
        __init__.py
        settings.py
        urls.py
        asgi.py
        wsgi.py
```

# 프로젝트 실행
## 1. venv 설정
```bash
$ source venv/bin/activate
```

## 2. 실행
```bash
$ cd myproject
$ python manage.py runserver
```