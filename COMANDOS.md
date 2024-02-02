# Comandos utilizados durante el proyecto

## Creación de proyecto Django

Crea la estructura y archivos de configuracion inicial para un proyecto de Django

```
django-admin startproject pacificgs
```

Más información en [documentación oficial de Django](https://docs.djangoproject.com/es/5.0/intro/tutorial01/)

## Ejecución del servidor de desarrollo

Se ejecuta por defecto en 127.0.0.1 (localhost) en puerto 8000:

```
cd pacificgs
python manage.py runserver
```

Para cambiar el puerto especificarlo al final del comando, ejemplo en puerto 8080:

```
python manage.py runserver 8080
```

Para escuchar en todas las IPs publicas (accesible desde la red):

```
python manage.py runserver 0.0.0.0:8000
```


Para escuchar desde una IP en especifico (Suponiendo que el servidor tiene IP 192.168.1.2):

```
python manage.py runserver 192.168.1.2:8000
```

## Creación de aplicación

Dentro del directorio del proyecto (donde esta ubicado manage.py) ejecutar el siguiente comando para crear una aplicación llamada inicio:

```
python manage.py startapp inicio
```

Esto creara otro directorio con la estructura requerida