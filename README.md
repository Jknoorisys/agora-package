# Laravel Package to Generate Agora Token

### Steps
_ composer require noorisys/agora
_ add (\Noorisys\Agora\Providers\AgoraServiceProvider::class,) in config/app.php providers section
_ run php artisan publish:vendor --force
_ select Noorisys\Agora\Providers\AgoraServiceProvider tag 
_ run migrations
_ hit apis on postman
