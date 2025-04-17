# 🎉 DEMO Laravel Breeze Cookie Consent

A Laravel package to manage cookie consent with ease. Provides customizable banners, GDPR/CCPA compliance, and seamless integration into Laravel Blade views. Ideal for websites needing user consent for cookies and tracking scripts.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

- Create Project

```shell
composer create-project laravel/laravel example-app
```

- Install Package

```shell
composer require devrabiul/laravel-cookie-consent
```

- Configure Environment

```shell
cp .env.example .env
```

- Publish Config File

```shell
php artisan vendor:publish --provider="Devrabiul\CookieConsent\CookieConsentServiceProvider"
```

- Update HTML File

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laravel Cookie Consent Demo</title>
    {!! CookieConsent::styles() !!}
</head>
<body>
 
    <!-- Your amazing content -->
 
    {!! CookieConsent::scripts() !!}
</body>
</html>
```

- Migrate

```
php artisan breeze:install
 
php artisan migrate
npm install
npm run dev
```

### 🏆 Run

- [http://localhost:8000/](http://localhost:8000/) username : `admin` password : `admin`

```shell
php artisan serve
```
