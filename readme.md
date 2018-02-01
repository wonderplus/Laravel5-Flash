Using laracasts/flash with Laravel  
====

https://github.com/laracasts/flash
https://packagist.org/packages/laracasts/flash


## Å° flash installation 

```
composer require laracasts/flash
```


<config/app.php>
```
'providers' => [
    Laracasts\Flash\FlashServiceProvider::class,
];
```



----------

php artisan config:cache  
composer dump-autoload  



php artisan serve  
http://localhost:8000/  
