

## Install This Project

set database config at .env file

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_product
DB_USERNAME=root
DB_PASSWORD=
```

open cmd go to project directory

run code:
```
php artisan migrate
php artisan db:seed
php artisan serve
```

default email and password for admin access

```
email: admin@email.com
password: 123456
```

NOTE : Make new user and assign role from admin module like (product list) then user can able to view product.

