
---

## Laravel Backend

## Проект делался при наличии laravel Herd

npm install - composer install - первым делом

### 1. Клонирование и установка
```bash
git clone https://github.com/your-repo/backend.git
```
```bash
cd backend
```
```bash
composer install
```
```bash
cp .env.example .env
```
```bash
php artisan key:generate
```
### 2. Поднять базу данных 

```bash
APP_URL=http://testtoner.test
DB_DATABASE=your_database
DB_USERNAME=your_user
DB_PASSWORD=your_passwor

php artisan migrate
```

### 3. Миграции и Passport 

```bash
php artisan passport:install
php artisan passport:client --public
php artisan migrate
```
npm run dev - запуск веб-сервера || php artisan serve
