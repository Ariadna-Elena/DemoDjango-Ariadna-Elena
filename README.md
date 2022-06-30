# DemoDjango-Ariadna-Elena

Django es un marco Python de alto nivel diseñado para un desarrollo web rápido, seguro y escalable. Incluye soporte para enrutamiento de URL, plantillas de página y trabajo con datos basado en el tutorial [Uso de Django en Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-django).
Para este demo deberá contar con los siguientes requisitos:
*Editor de código (Visual Studio Code) con extensiones Python
*Lenguaje de programación Python

Para ejecutar el demo realice los siguientes pasos:

1. Cree un entorno virtual dentro de una carpeta específica.
    Linux:
    `sudo apt-get install python3-venv`  #Si es necesario
    `python3 -m venv .venv`
    `source .venv/bin/activate`
    Windows:
    `py -3 -m venv .venv`
    `.venv\scripts\activate`
2. Instale paquetes con `pip3 install -r requirements.txt`.
3. Actualice pip en el entorno virtual ejecutando `python -m pip install --upgrade pip`.
4. Instale Django en el entorno virtual ejecutando `python -m pip install django`.
5. Cree e inicialice la base de datos ejecutando `python manage.py migrate`.
6. Para verificar el proyecto Django ejecute el comando `python manage.py runserver`.
7. Inicie sesión con django como usuario y contraseña o bien, cree un superusuario ejecutando `python manage.py createsuperuser --username=<username> --email=<email>`.