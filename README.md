Necesitaremos una cuenta de Github 
Una cuenta en Render 
crear el repositorio en GitHub
Entra a tu cuenta de GitHub.
Crea un nuevo repositorio 
Dentro de ese repositorio, guarda o sube los siguientes elementos:
Los archivos de Odoo .
hay una carpeta llamada custom_addons donde pondrás tus módulos personalizados.
Un archivo de configuración odoo.conf que indica cómo debe funcionar el sistema.
tambien puedes crear un archivo Dockerfile si quieres que Render construya todo automáticamente .
 GitHub guardará tu Odoo y Render lo ejecutará en línea.
Crear los servicios en Render
Render necesita dos cosas para que Odoo funcione:
Una base de datos PostgreSQL 
Una aplicación web 
Crear la base de datos
Entra en tu cuenta de Render.
Ve a “New” → “Database” → “PostgreSQL”.
Guarda la información que te muestra Render
Esa información la usaremos después para conectar Odoo con la base de datos.
Crear el servicio web de Odoo
En Render, haz clic en New - Web Service
Conecta tu cuenta de GitHub y elige el repositorio que creaste 
Render leerá tu proyecto y pedirá algunos datos:
Nombre del servicio 
Comando de inicio: aquí Render necesita saber cómo arrancar Odoo.
 Render construirá el sistema y lo pondrá en marcha.
Después de unos minutos, Render te mostrará una URL pública, Al entrar ahí, verás la pantalla inicial de Odoo.

