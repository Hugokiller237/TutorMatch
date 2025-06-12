Requisitos previos
● PHP >= 8.1
● Composer
● MySQL o MariaDB
● XAMPP, Laragon o cualquier entorno local con Apache y MySQL
● Node.js y npm (para compilar assets si fuera necesario)
Pasos de instalación
1. Una vez descargado el proyecto, debes ponerlo en la carpeta de htdocs dentro de la carpeta XAMPP.
2. Dentro de tu proyecto, en la consola de comandos, debes poner el siguiente comando:
composer install
3. Tras esto asegúrate que el archivo .env esté correctamente configurado para ti.
4. Tras esto solo tienes que usar este comando para rellenar la base de datos:
php artisan migrate
5. Y por último para poner en marcha el servidor local este otro comando:
php artisan serve
