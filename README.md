# Магазин мебели на Django

Данный проект представляет собой практическое применине знаний по  **Django**, **PostgreSQL**, для создания тг  бота для пиццерии.

####  Стек

- **PYTHON**: PYTHON 3.11.9
- **DJANGO**: [DJANGO 4.2.8](https://docs.djangoproject.com/en/4.2/)
- **ORM**: Django ORM
- **База данных**: [PostgreSQL](https://www.postgresql.org/)

### Структура проекта

```
├── .env
├── .gitignore
├── app/
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py


├── carts/
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── mixins.py
│   ├── models.py
│   ├── templates/
│   │   ├── carts/
│   │   │   ├── includes/
│   │   │   │   ├── included_cart.html
│   ├── templatetags/
│   │   ├── carts_tags.py
│   ├── tests.py
│   ├── urls.py
│   ├── utils.py
│   ├── views.py

├── common/
│   ├── mixins.py

├── fixtures/
│   ├── goods/
│   │   ├── category.json
│   │   ├── product.json

├── goods/
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── templates/
│   │   ├── goods/
│   │   │   ├── catalog.html
│   │   │   ├── product.html
│   ├── templatetags/
│   │   ├── goods_tags.py
│   ├── tests.py
│   ├── urls.py
│   ├── utils.py
│   ├── views.py


├── main/
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── templates/
│   │   ├── main/
│   │   │   ├── about.html
│   │   │   ├── index.html
│   ├── tests.py
│   ├── urls.py
│   ├── views.py

├── manage.py

├── orders/
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── migrations/
│   ├── models.py
│   ├── templates/
│   │   ├── orders/
│   │   │   ├── create_order.html
│   ├── tests.py
│   ├── urls.py
│   ├── views.py


├── static/
│   ├── deps/
│   │   ├── css/
│   │   │   ├── bootstrap/
│   │   │   │   ├── bootstrap.min.css
│   │   │   ├── my_css.css
│   │   │   ├── my_footer_css.css
│   │   ├── favicon/
│   │   │   ├── android-chrome-192x192.png
│   │   │   ├── android-chrome-512x512.png
│   │   │   ├── apple-touch-icon.png
│   │   │   ├── favicon-16x16.png
│   │   │   ├── favicon-32x32.png
│   │   │   ├── favicon.ico
│   │   │   ├── site.webmanifest
│   │   ├── icons/
│   │   │   ├── basket2-fill.svg
│   │   │   ├── box-arrow-in-left.svg
│   │   │   ├── box-arrow-in-right.svg
│   │   │   ├── cart-plus.svg
│   │   │   ├── facebook.svg
│   │   │   ├── github.svg
│   │   │   ├── google.svg
│   │   │   ├── grid-fill.svg
│   │   │   ├── trash3-fill.svg
│   │   ├── images/
│   │   │   ├── baseavatar.jpg
│   │   │   ├── bg-image.jpg
│   │   │   ├── goods/
│   │   │   │   ├── bedside table.jpg
│   │   │   │   ├── corner sofa.jpg
│   │   │   │   ├── double bed.jpg
│   │   │   │   ├── flower.jpg
│   │   │   │   ├── kitchen table 2.jpg
│   │   │   │   ├── kitchen table.jpg
│   │   │   │   ├── office chair.jpg
│   │   │   │   ├── plants.jpg
│   │   │   │   ├── set of tea table and three chairs.jpg
│   │   │   │   ├── set of tea table and two chairs.jpg
│   │   │   │   ├── sofa.jpg
│   │   │   │   ├── strange table.jpg
│   │   │   ├── Not found image.png
│   │   ├── js/
│   │   │   ├── bootstrap/
│   │   │   │   ├── bootstrap.bundle.min.js
│   │   │   ├── jquery/
│   │   │   │   ├── jquery-3.7.0.min.js
│   │   │   ├── jquery-ajax.js

├── templates/
│   ├── base.html
│   ├── includes/
│   │   ├── cart_button.html
│   │   ├── notifications.html

├── users/
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── migrations/
│   ├── models.py
│   ├── templates/
│   │   ├── users/
│   │   │   ├── login.html
│   │   │   ├── profile.html
│   │   │   ├── registration.html
│   │   │   ├── users_cart.html
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
```










## Начало работы

1. Клонируйте репозиторий:
```bash
git clone https://github.com/marutyunyan-20/PathP_Pizza_bot_test.git.
```

2.Создайте и активируйте свою виртуальную среду:
```bash
python -m venv .venv
```
Windows:
```powershell
.venv/Scripts/activate
```
Linux и MacOS-systems:
```bash
source .venv/bin/activate
```

3. Установите зависимости:
```bash
pip install -r requirements.txt
```

3. Запустите бота:
Windows:
```bash
python manage.py 
