# Laravel Package to Generate Agora Token

### Steps
composer require noorisys/agora

add (\Noorisys\Agora\Providers\AgoraServiceProvider::class,) in config/app.php providers section

run php artisan publish:vendor --force

select Noorisys\Agora\Providers\AgoraServiceProvider tag 

run migrations

hit apis on postman
