# How to use this app

1. **Install dependencies**  
   `composer u`  
   `npm i`
2. **Run docker**  
   `docker compose build`  
   `docker compose up -d`
3. **Go to docker fpm container**  
   `docker ps | grep fpm`  
   copy id (first column)  
   `docker exec -it <id> bash`  
4. **Create .env file**  
   `cp .env.example .env`
5. **Generate laravel key**  
   `php artisan key:generate`
6. **Migrate**  
   `php artisan migrate`
7. **Seed db**  
   `php artisan db:seed`
8. App is available on http://localhost:8051

