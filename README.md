# Restful API Student

Repository ini dibuat untuk mempelajari lebih dalam tentang pembuatan restful api menggunakan framework Laravel

## Tech Stack

**Framework:** Laravel 13

**Database:** Mysql

## Endpoint & Features

Dokumentasi API: <https://documenter.getpostman.com/view/25808118/2sBXqDt3pK>
Dokumentasi JWT: <https://jwt-auth.readthedocs.io/en/develop/laravel-installation/>

- Authentication (JWT)
- Get all data
- Get single data
- Create data
- Edit data
- Delete data

## Run Locally

Clone the project

```bash
  git clone https://github.com/syrsdev/restful-api-playground
```

Go to the project directory

```bash
  cd restful-api-playground
```

Install dependencies

```bash
  composer install

  npm install
```

Environment

```bash
  cp .env.example .env  
```

Database & App setup

```bash
  php artisan migrate
  or with seeder
  php artisan migrate:fresh --seed

  php artisan key:generate
  php artisan jwt:secret
```

Start the server

```bash
  composer run dev
```

## Authors

- [Surya Nata Ardhana](https://www.github.com/syrsdev)
