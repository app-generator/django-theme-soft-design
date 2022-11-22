# [Django Theme Soft](https://github.com/app-generator/django-theme-soft-design)

Modern template for **Django** coded on top of **Soft UI Design**, an open-source `Boostrap 5` design from `Creative-Tim`. 

> NOTE: The theme aims to style the pages for the common users (not admin section).

**Design Version**: https://github.com/creativetimofficial/soft-ui-design-system `v1.0.9`

<br>

**Links & Resources**

- UI Kit: [Soft UI Design](https://www.creative-tim.com/product/soft-ui-design-system?AFFILIATE=128200) `v3.0.4` by Creative-Tim
- [Django Theme Soft UI Design](#) - `playground project` (coming soon)

<br />

![Soft UI Design - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/168812602-e35bad42-823f-4d3e-9d13-87a6c06c5a63.png)

<br />

## Why `Django Material Kit`

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

> Add `theme_soft_design` urls in your Django Project `urls.py` file.

```python
    from django.urls import path, include

    urlpatterns = [
        ...
        path('', include('theme_soft_design.urls')),
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

## How to use the theme

> Ordinary users set up

## Screenshots

@todo

<br />

---
**[Django Theme Soft](https://github.com/app-generator/django-theme-soft-design)** - Modern KIT Integration provided by **[AppSeed](https://appseed.us/)**
