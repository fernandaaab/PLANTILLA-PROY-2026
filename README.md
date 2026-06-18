# PROY-2026-GRUPO1

Repositorio del grupo 1 para el proyecto del ramo *Proyecto Inicial (IWG400)* – 2026.

## 👥 Integrantes del grupo

| Nombre y Apellido | Usuario GitHub | Correo USM               | Rol USM      |
| ----------------- | -------------- | ------------------------ | ------------ |
| Alvaro Campos | @alvarokokeee      | acamposro@usm.cl | 202630031-5 |
| Joaquin Silva  | @Joacosilva0      | jsilvapa@usm.cl| 202630020-k |
| Fernanda Barrientos | @fernandaaab      | fbarrientos@usm.cl | 202630011-0 |
| Julianna Moraga | @Julii-m      | jmoragaa@usm.cl | 202630014-5 |

## 📝 Descripción breve del proyecto

> Este proyecto es una idea cuyo propósito es simplificar la vida de los estudiantes a través de una página web que les permita solicitar todo tipo de alimentos y bebidas que cada establecimiento ofrezca. De esta forma, se busca ahorrar tiempo a aquellos estudiantes que no cuentan con el tiempo suficiente entre clases y tienen la necesidad de comer o tomar algo.


---

## 🎯 Objetivos

- Objetivo general:
  - Facilitar la compra de alimentos en los kioskos, descongestionando el flujo de pesonas al momento de comprar. Optimizando el tiempo de los estudiantes, profesores y funcionarios. 
- Objetivos específicos:
  1. Programar una página web.
  2. Diseño gráfico de la página web.
  3. Incluir inventario de los diferentes quioscos.
  4. Implementar Filacero en la comunidad (Casa Central).

---

## 🧩 Alcance del proyecto

>   Este proyecto está pensado para ser utilizado dentro de la USM en todo momento en que el estudiante lo necesite. La idea es que llegue a ser útil para cada estudiante y funcionario de la universidad, logrando así ahorrar la mayor cantidad de tiempo posible.

Una limitación que existe en nuestro proyecto es que no es posible incluir un sistema de pago dentro de la página web, lo que finalmente haría mucho más rápido el proceso de compra de productos.


---

## 🛠️ Tecnologías y herramientas utilizadas

- Lenguaje(s) de programación:
  - Python, Visual Studio Code, Django, Chatgpt y Devin Ai.

---

## 🗂️ Estructura del repositorio

```
C:\USERS\ALONS\DOWNLOADS\FILACERO_FINAL\FILACERO
│   db.sqlite3
│   manage.py
│   README.md
│   requirements.txt
│   
├───config
│   │   asgi.py
│   │   settings.py
│   │   urls.py
│   │   wsgi.py
│   │   __init__.py
│   │   
│   └───__pycache__
│           settings.cpython-311.pyc
│           urls.cpython-311.pyc
│           wsgi.cpython-311.pyc
│           __init__.cpython-311.pyc
│           
├───static
│   ├───css
│   │       style.css
│   │       
│   └───js
│           index.js
│           
├───templates
│   │   base.html
│   │   index.html
│   │   
│   ├───adminpanel
│   │       comercios.html
│   │       dashboard.html
│   │       usuarios.html
│   │       
│   ├───auth
│   │       login.html
│   │       registro.html
│   │       
│   ├───carrito
│   │       carrito.html
│   │       
│   ├───comercio
│   │       dashboard.html
│   │       pedidos.html
│   │       productos.html
│   │       producto_form.html
│   │       
│   └───usuario
│           inicio.html
│           pedidos.html
│           
└───web
    │   admin.py
    │   apps.py
    │   data.py
    │   forms.py
    │   models.py
    │   tests.py
    │   views.py
    │   __init__.py
    │   
    ├───management
    │   │   __init__.py
    │   │   
    │   └───commands
    │           seed.py
    │           __init__.py
    │           
    ├───migrations
    │   │   0001_initial.py
    │   │   0002_remove_pedido_productos_alter_pedido_usuario_and_more.py
    │   │   0003_carrito_itemcarrito.py
    │   │   __init__.py
    │   │   
    │   └───__pycache__
    │           0001_initial.cpython-311.pyc
    │           0002_remove_pedido_productos_alter_pedido_usuario_and_more.cpython-311.pyc
    │           0003_carrito_itemcarrito.cpython-311.pyc
    │           __init__.cpython-311.pyc
    │           
    └───__pycache__
            admin.cpython-311.pyc
            apps.cpython-311.pyc
            forms.cpython-311.pyc
            models.cpython-311.pyc
            views.cpython-311.pyc
            __init__.cpython-311.pyc
```

---

## 🚀 Instrucciones de Instalacion y Uso

1. Instalar Visual Studio Code, Python y Django.
2. Descargar el zip predeterminado del proyecto.
3. Con ciertos comandos hacer correr el servidor.
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
   .venv\Scripts\Activate.ps1
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py seed
   python manage.py runserver
4. Abrir página web mediante el link que proporciona el Visual Studio Code.

---

## 📐 Diseño del Sistema
No se utilizó hardware para el desarrollo de este proyecto.

---

## 📅 Cronograma de trabajo

[Carta Gantt](https://google.com)
- https://usmcl-my.sharepoint.com/:x:/g/personal/jsilvapa_usm_cl/IQC5Aoh3ogjrTJvcVkKL6fXFAaAwK-dLrdkADH6upyXzTjE?e=l2g6h3
---

## 📚 Bibliografía

https://app.devin.ai/sessions/16b3d498be7846b3bb6ae939a8183ee1?tab=DEPLOY_PYTHONANYWHERE.md

---

## 📌 Notas adicionales

- Video demostración

Para ver el funcionamiento de la pagina web, acceda al siguiente enlace:

Video del proyecto:
https://youtu.be/OvWPdG-vjG4
