# buyerda ishlatilgan

# laratrust sayt 
    https://laratrust.santigarcor.me/docs/8.x/installation.html
# laratrust install
    1  composer require santigarcor/laratrust
    2  php artisan vendor:publish --tag="laratrust"
    3  php artisan laratrust:setup
    4  composer dump-autoload
    5  php artisan migrate

# laratrust Seeder
    1  php artisan laratrust:seeder
    2  php artisan vendor:publish --tag="laratrust-seeder"
    3  composer dump-autoload

# Auth install breeze
    1  composer require laravel/breeze --dev
    2  php artisan breeze:install
    3  php artisan migrate
    4  npm install
    5  npm run dev
