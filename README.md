## Учебный проект
Для запуска проекта выполните следующие команды:
```sh
git clone https://github.com/sheikina-ev/learn-laravel-10.loc
```

```sh
cd learn-laravel-10.loc
```
```sh
composer install
```

```sh
php artisan key:generate
```

Переименуйт файл .env.example в .env и пропишите настройки подключения к БД

```sh
php artisan migrate --seed
```

