# Laravel Package to Generate Agora Token
[![Latest Stable Version](http://poser.pugx.org/phpunit/phpunit/v)](https://packagist.org/packages/phpunit/phpunit) [![Total Downloads](http://poser.pugx.org/phpunit/phpunit/downloads)](https://packagist.org/packages/phpunit/phpunit) [![Latest Unstable Version](http://poser.pugx.org/phpunit/phpunit/v/unstable)](https://packagist.org/packages/phpunit/phpunit) [![License](http://poser.pugx.org/phpunit/phpunit/license)](https://packagist.org/packages/phpunit/phpunit) [![PHP Version Require](http://poser.pugx.org/phpunit/phpunit/require/php)](https://packagist.org/packages/phpunit/phpunit)

### Steps
composer require noorisys/agora

add (\Noorisys\Agora\Providers\AgoraServiceProvider::class,) in config/app.php providers section

run php artisan publish:vendor --force

select Noorisys\Agora\Providers\AgoraServiceProvider tag 

run migrations

hit apis on postman
