# [Django Theme Soft](https://github.com/app-generator/django-theme-soft-design)

Modern template for **Django** coded on top of **Soft Design**, an open-source `Boostrap 5` design from `Creative-Tim`. 

> Actively supported by [AppSeed](https://appseed.us/) via `Email` and `Discord`.

<br>

**Links & Resources**

- [Django Theme Soft](https://django-soft-ui-free.appseed-srv1.com/) - LIVE Demo
- [Django Theme Soft](https://github.com/app-generator/django-theme-soft-design_p) - `playground project` 
- UI Kit: [Soft UI Design](https://www.creative-tim.com/product/soft-ui-design-system?AFFILIATE=128200) `v1.0.9` by Creative-Tim

<br />

![Soft UI Design - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168812602-e35bad42-823f-4d3e-9d13-87a6c06c5a63.png)

<br>

## `Video Presentation`

> This material provides `more information` about this library and the `playground project`.

[![Django Theme Material Kit - Video Presentation.](https://user-images.githubusercontent.com/51070104/203528345-8ad10b43-2f38-4053-ab7c-88881ff584aa.png)](https://www.youtube.com/watch?v=sNY_ZwChQNM)

<br />

## Why `Django Soft UI Design`

- Modern `Bootstrap 5` Design
- `Responsive Interface`
- `Minimal Template` overriding
- `Easy integration`

<br />

## How to use it

<br />

> **Install the package** via `PIP` 

```bash
$ pip install django-theme-soft-design
// OR
$ pip install git+https://github.com/app-generator/django-theme-soft-design.git
```

<br />

> Add `theme_soft_design` application to the `INSTALLED_APPS` setting of your Django project `settings.py` file:

```python
INSTALLED_APPS = [
    "django.contrib.admin",
    "django.contrib.auth",
    "django.contrib.contenttypes",
    "django.contrib.sessions",
    "django.contrib.messages",
    "django.contrib.staticfiles",

    'theme_soft_design',          # <-- NEW
]
```

<br />

> Update project `settings.py` file to include (at the end of the file):
```python
    LOGIN_REDIRECT_URL = '/'
    EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'
```

<br />

> Add `theme_soft_design` urls in your Django Project `urls.py` file.

```python
from django.urls import path, include             # <-- UPD with 'include' directive 

urlpatterns = [
    ...
    path('', include('theme_soft_design.urls')),  #  <-- NEW
]
```

<br />

> **Collect static** if you are in `production environment`:

```bash
$ python manage.py collectstatic
```

<br />

> **Start the app**

```bash
$ # Set up the database
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Create the superuser
$ python manage.py createsuperuser
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
```

<br />

## Screenshots

![Django Theme Soft UI Design - Cover.](https://user-images.githubusercontent.com/51070104/203517522-f913cc7f-6aa9-4f71-9582-74e1923df05d.jpg)

<br />

> [Django Theme Soft](https://github.com/app-generator/django-theme-soft-design) - `Author Page`

![Django Theme Soft UI Design - Author Page.](https://user-images.githubusercontent.com/51070104/203517708-124222e5-3823-4b27-82ca-7268dcea2699.jpg)

<br />

> [Django Theme Soft](https://github.com/app-generator/django-theme-soft-design) - `Team Component`

![Django Theme Soft UI Design - Team Component.](https://user-images.githubusercontent.com/51070104/203517888-0d327a87-48fc-4240-b009-fca1646c2782.jpg)

<br />

---
**[Django Theme Soft](https://github.com/app-generator/django-theme-soft-design)** - Modern KIT Integration provided by **[AppSeed](https://appseed.us/)**
