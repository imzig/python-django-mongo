# OS X - python-django-mongo
```설치 환경 - OS X 10.11 El Capitan```

1. python
2. django
3. with mongodb


[TOC]



## python 설치
installer 다운로드
https://www.python.org/downloads/

*++
가상환경을 만들고
실제 os의 환경과 다르게 구성하여 개발을 진행 할 수 있음.
본 튜토리얼은 가상환경을 만드는것으로 함.
++*


### 가상환경 설정

```
$ python3 -m venv test
```

### 가상환경 접속

```
$ source test/bin/activate
(test) $ 
```

### 가상환경에서 나가기
```
(test) $ deactivate
$
```


## django 설치

```
(test) $ pip install Django
```


### django project 만들기
```
(test) $ django-admin startproject testpjt
```


### django project 실행 및 접속
```
(test) $ cd testpjt
(test) $ ./manage.py runserver
```
