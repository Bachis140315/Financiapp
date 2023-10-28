# financiapp
Application made with DJango to manage your personal finances, using your own account.

# Grupo 12 - Proyecto del curso CC4401 2023-1

¡Bienvenido al repositorio del Grupo 12 para el curso CC4401 del año 2023-1!

## Descripción del proyecto

Este proyecto es parte del curso CC4401 y tiene como objetivo desarrollar una aplicación web especializada en finanzas personales llamada "Financiapp". El proyecto está siendo desarrollado por el Grupo 12 y consta de las siguientes funcionalidades principales:

- Registro de inicio de sesión de usuarios.
- Visualización del saldo actual del usuario.
- Registro y visualización de los últimos movimientos financieros.
- Agregar nuevas transacciones financieras.
- Filtrar las transacciones financieras del usuario, en base a una categoría y/o un rango de fechas.
- Editar y eliminar las transacciones del ususario.

## Estructura del repositorio

El repositorio está organizado de la siguiente manera:
#### Accounts
- `/templates`: Dos Códigos fuentes de la aplicación web en html que contienen el login y register. Además, maneja las vistas, modelos y configuraciones de estos mismo.
#### Categories
- Donde se encuentra toda la configuración para que el usuario pueda manejar las categorias de sus transacciones. Del mismo modo, contiene los modelos, vistas y configuraciones de estas.
#### Divaa
- En este directorio esta guardada toda la configuración del proyecto, como *urls* validas y la inicialización de Django.
#### Fixtures
- Donde se guarda toda la información del proyecto, ya sea usuarios, transacciones y categorias.
#### Transsactions
- `/templates`: Tres Códigos de la aplicación web en html que contienen la página principal, el ingreso de nuevas transacciones y la descripción de cada transacción del usuario. Igualmente, se encuentras presentes las vistas, modelos y configuraciones de estas páginas. 

Además, cada directorio que contenian *templates* vienen con el elemento `/static`, el cual era una carpeta con archivos CSS que se encargaban de todo el diseño de los archivos html. 

## Configuración del entorno de desarrollo

Para configurar el entorno de desarrollo y ejecutar el proyecto de manera local, sigue los siguientes pasos:

1. Clona este repositorio en tu máquina local: `git clone https://github.com/DCC-CC4401/2023-1-Grupo-12.git`.
2. Navega al directorio del proyecto: `cd 2023-1-Grupo-12`.
4. Configura las variables de entorno necesarias para la aplicación.
5. Para poder utilizar esta app hay que instalar los paquetes que el proyecto requiere. Para esto instalaremos la lista de paquetes que viene en el archivo requirements.txt con el siguiente comando (RECUERDA TENER EL AMBIENTE VIRTUAL ACTIVO) ` pip install -r requirements.txt`.
6. El project de Django trae algunas tablas de la base de datos pre hechas, por lo tanto tenemos que navegar e ir a la carpeta **divaa**, y avisar que actualice sus tablas con el siguiente comando `python manage.py migrate`.
7. Finalmente, ejecuta la aplicación: `python manage.py runserver`.


## Contacto

Si tienes alguna pregunta o consulta, no dudes en contactar al Grupo 12 a través de la sección de Issues de este repositorio.

¡Gracias por tu interés en nuestro proyecto! Esperamos que encuentres útil y emocionante nuestra aplicación web "Financiapp".
