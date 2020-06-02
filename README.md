# Lumen Route List Display

[![License](https://poser.pugx.org/appzcoder/lumen-routes-list/license.svg)](https://packagist.org/packages/appzcoder/lumen-routes-list)


## Installation

1. Run
    ```
    composer require zitrone475/lumen-routes-command
    ```

2. Add service provider into **/bootstrap/app.php** file.
    ```php
    $app->register(Appzcoder\LumenRoutesList\RoutesCommandServiceProvider::class);
    ```
3. Run ```composer dump-autoload```

## Commands

```
php artisan route:list
```


## Author

<a href="http://www.sohelamin.com">Sohel Amin</a>
