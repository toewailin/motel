# Motel

## Process

create project
```bash
$ laravel new motel
$ cd motel
$ npm i && npm run build
$ code .
```

config
```php
DB_CONNECTION=mariadb
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=motel
DB_USERNAME=root
DB_PASSWORD=root
```

create database
```bash
$ mysql -u root -p
$ Enter your password:
CREATE DATABASE motel;
```

migrate
```bash
$ php artisan migrate
$ php artisan db:seed
```

run the application
```bash
$ composer run dev
```

clone the site
```bash
$ http://www.httrack.com/
$ brew install httrack
$ httrack "https://www.yanolja.com" -O ~/Desktop/yanolja-site --depth=3 --robots=0 --user-agent="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/91.0.4472.124 Safari/537.36"

```