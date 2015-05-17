## Scafold ##

### Installation ###

Add Scafold to your composer.json file to require Scafold :
```
    require : {
        "laravel/framework": "5.1.*",
        "bestmomo/scafold": "1.0.*"
    }
```

Update Composer :
```
composer update
```

The next required step is to add the service provider to config/app.php :
```
    'Bestmomo\Scafold\ScafoldServiceProvider',
```

### Publish ###

The last required step is to publish views and assets in your application with :
```
    php artisan vendor:publish
```

Congratulations, you have successfully installed Scafold ! But there is a last step...

