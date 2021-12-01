# Laravel Nova: Uuid support

I just didn't like the implementation of the migrations table on the original hack to get Uuid support with laravel nova

So this is cleaner and more acceptable in my world

### Usage

Note that you should only use this package in Laravel Nova projects.

```bash
# install the package
composer require itsmejoshua/laravel-nova-uuid-support

# run your migrations
php artisan migrate
```

That's it, your Laravel Nova installation can now handle resources and users with string identifiers.
