### Init
```
cp .env.example .env
composer install
php artisan vendor:publish --provider="Encore\Admin\AdminServiceProvider"
php artisan vendor:publish --tag=laravel-admin-grid-lightbox
php artisan vendor:publish --tag=laravel-admin-wangEditor


php artisan key:generate


php artisan migrate --path database\migrations\
php artisan db:seed
```




### Back
```
php artisan migration:generate
php artisan admin:export-seed --users
php artisan iseed products_contract
php artisan iseed products_exchange
php artisan iseed wallet_code
```


