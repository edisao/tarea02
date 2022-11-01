# Creando un proyecto con Wagtail

Para crear un proyecto seguimos los siguientes pasos:

# Instalando la librería

`{ pip install wagtail }`

![alt text](https://github.com/edisao/tarea02/blob/main/images/imagen-1.png?raw=true)

# Inicializamos el proyecto

`{ wagtail start modeloscms }`

![alt text](https://github.com/edisao/tarea02/blob/main/images/imagen-2.png?raw=true)

# Ingresamos a la carpeta creada en el paso anterior

`{ cd modeloscms }`

![alt text](https://github.com/edisao/tarea02/blob/main/images/imagen-4.png?raw=true)

# Instalamos los requerimientos

`{ pip install -rrequirements.txt }`

![alt text](https://github.com/edisao/tarea02/blob/main/images/imagen-5.png?raw=true)

# Generamos la migración del proyecto

`{ python manage.py migrate }`

![alt text](https://github.com/edisao/tarea02/blob/main/images/imagen-6.png?raw=true)

# Creamos un super usuario

`{ python manage.py createsuperuser }`

![alt text](https://github.com/edisao/tarea02/blob/main/images/imagen-7.png?raw=true)

# Levantamos el servidor

`{ python manage.py runserver }`

![alt text](https://github.com/edisao/tarea02/blob/main/images/imagen-8.png?raw=true)
