# Учебный проект: социальная сеть Yatube.

__Yatube__ это социальная сеть, где пользователи могут публиковать свои посты, оставлять комментарии к постам других пользователей, а также подписываться на других авторов.
Посты могут быть привязаны к тематической группе, на которую также можно подписаться.

 ## Технологии

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![PythonAnywhere](https://img.shields.io/badge/pythonanywhere-%232F9FD7.svg?style=for-the-badge&logo=pythonanywhere&logoColor=151515)
 
 ## Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке:
  ```
  git@github.com:EvKutyashov/yatube.git
  ```
  ```
  cd yatube
  ```
2. Cоздать и активировать виртуальное окружение:

* Если у вас **Windows**:
```
python -m venv venv
```
```
source venv/Scripts/activate
```
* Если у вас **Linux** или **macOS**:
```
python3 -m venv venv
```
```
source venv/bib/activate
```
3. Установоить зависимости:
```
pip install -r requirements.txt
```
4. Перейти в дерикторию `yatube` выполнить миграции и создать супер-пользователя:
```
cd yatube
```
```
python manage.py makemigrations
```
```
python manage.py migrate
```
```
python manage.py createsuperuser
```
5. Запустить сервер разработки:
```
python manage.py runserver
```
### Автор
**Евгений Кутяшов**
<br>

<a href="https://t.me/e_kutyashov" target="_blank">
<img src=https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white />
</a>
