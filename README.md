# Proyecto de CS50: LEJ

Este proyecto trata sobre un servicio de alojamiento en la nube construido en flask, parecido a Google Drive.

## Instalación

Para instalarlo primero hay que ir a la carpeta del proyecto e instalar las dependencias usando los comandos

` python -m venv [nombre_del_entorno]  `
` [nombre_del_entorno]/scripts/activate `
` pip install -r requirements.txt `

Luego hay que ejecutar el script de la base de datos sql server y al final ejecutar el programa con 

` flask run `

## Problemas

- Todos los archivos están siendo guardados en la base de datos por lo que es ineficiente
- Los archivos comprimidos se guardan como archivos genéricos por lo que se pierde su contenido
- No estoy seguro si el correo que envia la verificacion de cuentas sigue activo
- Casi todo el código a excepción de unas pocas funciones está en el archivo ==app.py== por lo que es dificil de leer (código spaguetti).