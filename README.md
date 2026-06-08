## installation

1. run xampp apache and mysql
2. add new db courtnest_db
3. open project in vscode
4. open .env and set db_database = courtnest_db
5. run these commands :
    - composer install
    - php artisan key:generate
    - php artisan migrate --seed
    - npm install
    - npm run dev
    - php artisan serve