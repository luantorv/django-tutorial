# DJANGO Tutorial

Activar el entorno virtual:
`Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process`
`.\django\Scripts\activate`

### Tutorial Link

`https://docs.djangoproject.com/es/5.2/intro/tutorial01/`

### Levantar el servidor de Django

`Django\djangotutorial> py manage.py runserver`

### Correr lo tests de Polls

`Django\djangotutorial> py manage.py test polls`

>[NOTE]
>Terminé la tercera parte del tutorial.
>Después, empezar desde la parte 4

# Recuerde la guía de tres pasos para hacer cambios de modelo:

- Cambie sus modelos (en models.py).

- Ejecute el comando python manage.py makemigrations para crear migraciones para esos cambios

- Ejecute el comando python manage.py migrate para aplicar esos cambios a la base de datos.