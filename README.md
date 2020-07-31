# API Rest Backend FLutter

1. En consola ejecutar: composer install
2. Renombrar el archivo env.example a .env
3. Actualizar el atributo DB_DATABASE, DB_USERNAME, DB_PASSWORD en el archivo .env (de acuerdo a la base de datos que se vaya a usar)
4. En consola ejecutar: php artisan key:generate
5. En consola ejecutar: php artisan jwt:secret
6. En consola ejecutar: php artisan migrate:fresh --seed
7. Para levantar el entorno local, en consola ejecutar: php artisan serve