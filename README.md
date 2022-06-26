# laravel9

# Installation
```bash
composer create-project laravel/laravel example-app
 
cd example-app
 
php artisan serve
```

# The laravel installer

```bash
composer global require laravel/installer
 
laravel new example-app
 
cd example-app
 
php artisan serve
```

# The laravel up git

```bash
laravel new example-app --git
```

```bash
laravel new example-app --git --branch="main"
```

```bash
laravel new example-app --github
```

```bash
laravel new example-app --github="--public"
```

```bash
laravel new example-app --github="--public" --organization="laravel"
```

The first time you run the Sail up command, Sail's application containers will be built on your local machine. This could take several minutes. Don't worry, subsequent attempts to start Sail will be much faster.

Once the application's Docker containers have been started, you can access the application in your web browser at: http://127.0.0.1:8000 or http://localhost:8000.
