# Info

Repositorio de la app web que creamos en el [Curso Práctico de Django: Aprende Creando 3 Webs de Udemy](https://www.udemy.com/course/curso-django-2-practico-desarrollo-web-python-3/).

---
## Web Playground

Web Playground es un proyecto avanzado y de especialización, centrado puramente en el backend. Aquí aprenderás a manejar la autenticación y el registro de usuarios, a crear secciones internas sólo para usuarios identificados, perfiles de usuario y lo mejor de todo: un sistema de mensajería privada.

---
## Web site

- [Acceder al sitio web](https://diegoosvaldo85.pythonanywhere.com/)


<img   src="https://github.com/doctsystems/webplayground/blob/master/bg.png" />

---
## Que es lo que hay?

Es un proyecto que contiene 5 apps:

- __Core__ - nucleo del proyecto
- __Pages__ - paginas de contenido visibles en el sitio web
- __Registration__ - autenticacion y registro y de usuarios
- __Profiles__ - gestion de perfiles publicos de los usuarios
- __Messenger__ - mensajeria entre usuarios a nivel de app

---
## Instalacion y Configuracion

### Prerequisitos

- pip package manager 
```
    $ pip --version
    pip 20.0.2 (python 3.7)
```

### Install

- Primero, clonar el repositorio:
```
    git clone https://github.com/doctsystems/webplayground.git
```

- Instalar dependencias
```
    $ pip install -r requirements.txt
```

### Config

- Configurar la base de datos
```
    'ENGINE': DB.engine,
    'NAME': DB.name,
```

### Running

```
    $ python manage.py makemigrations
    $ python manage.py migrate
    $ python manage.py runserver
```

---
## Built With
* [Django](https://www.djangoproject.com/) - The web framework for perfectionists with deadlines.
