# [Black Dashboard](https://appseed.us/generator/black-dashboard/) Django

Open-source **Django Dashboard** generated by `AppSeed` op top of a modern `Bootstrap` design. Designed for those who like bold elements and beautiful websites, **[Black Dashboard](https://appseed.us/generator/black-dashboard/)** is ready to help you create stunning websites and webapps. **Black Dashboard** is built with over 50 frontend individual elements, like buttons, inputs, navbars, nav tabs, cards, or alerts, giving you the freedom of choosing and combining.

<br />

> 🚀 Built with [Black Dashboard Generator](https://appseed.us/generator/black-dashboard/), timestamp: `2022-05-25 10:28`

- 👉 [Black Dashboard Django](https://appseed.us/product/black-dashboard/django/) - Product page
- 👉 [Black Dashboard Django](https://django-black-dashboard.appseed-srv1.com/) - LIVE Demo
- 👉 [Complete documentation](https://docs.appseed.us/products/django-dashboards/black-dashboard) - `Learn how to use and update the product`
- ✅ [PRO Version Available](#pro-version) - `enhanced UI` and more `features`   
  
<br />

> Features

- `Up-to-date dependencies`
- Database: `sqlite`
- UI-Ready app, Django Native ORM
- `Session-Based authentication`, Forms validation

<br />

![Black Dashboard - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/169471556-144ea706-0965-4f7d-8493-da9570085367.png)

<br />


## ✨ Start the app in Docker

> **Step 1** - Download the code from the GH repository (using `GIT`) 

```bash
$ # Get the code
$ git clone https://github.com/app-generator/django-black-dashboard.git
$ cd django-black-dashboard
```

<br />

> **Step 2** - Edit `.env` and remove or comment all `DB_*` settings (`DB_ENGINE=...`). This will activate the `SQLite` persistance. 

```txt
DEBUG=True

# Deployment SERVER address
SERVER=.appseed.us
```

<br />

> **Step 3** - Start the APP in `Docker`

```bash
$ docker-compose up --build 
```

Visit `http://localhost:85` in your browser. The app should be up & running.

<br />




## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/app-generator/django-black-dashboard.git
$ cd django-black-dashboard
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## ✨ Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:8000/register/`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:8000/login/`

<br />

## ✨ Code-base structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                               # Implements app configuration
   |    |-- settings.py                    # Defines Global Settings
   |    |-- wsgi.py                        # Start the app in production
   |    |-- urls.py                        # Define URLs served by all apps/nodes
   |
   |-- apps/
   |    |
   |    |-- home/                          # A simple app that serve HTML files
   |    |    |-- views.py                  # Serve HTML pages for authenticated users
   |    |    |-- urls.py                   # Define some super simple routes  
   |    |
   |    |-- authentication/                # Handles auth routes (login and register)
   |    |    |-- urls.py                   # Define authentication routes  
   |    |    |-- views.py                  # Handles login and registration  
   |    |    |-- forms.py                  # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/                     # Templates used to render pages
   |         |-- includes/                 # HTML chunks and components
   |         |    |-- navigation.html      # Top menu component
   |         |    |-- sidebar.html         # Sidebar component
   |         |    |-- footer.html          # App Footer
   |         |    |-- scripts.html         # Scripts common to all pages
   |         |
   |         |-- layouts/                   # Master pages
   |         |    |-- base-fullscreen.html  # Used by Authentication pages
   |         |    |-- base.html             # Used by common pages
   |         |
   |         |-- accounts/                  # Authentication pages
   |         |    |-- login.html            # Login page
   |         |    |-- register.html         # Register page
   |         |
   |         |-- home/                      # UI Kit Pages
   |              |-- index.html            # Index page
   |              |-- 404-page.html         # 404 page
   |              |-- *.html                # All other pages
   |
   |-- requirements.txt                     # Development modules - SQLite storage
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- manage.py                            # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />

## PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Black Dashboard is a premium Bootstrap Design now available for download in Django. Made of hundred of elements, designed blocks, and fully coded pages, Black Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Black Dashboard PRO Django](https://appseed.us/product/black-dashboard-pro/django/) - product page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Black Dashboard PRO - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/169471630-e96cec9b-ef57-4c06-9b36-62b9bbf255f3.png)

<br />

---
[Black Dashboard](https://appseed.us/generator/black-dashboard/) Django - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
