# A User Access Control Packages for Laravel

[![Packagist Version](https://img.shields.io/packagist/v/draftscripts/permission)](https://github.com/draftscripts/permission)
[![Total Downloads](https://img.shields.io/packagist/dt/draftscripts/permission)](https://github.com/draftscripts/permission)

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

We invest a lot of resources into creating [best in class open source packages](https://draftscripts.com/open-source). You can support us by [buying one of our paid products](https://draftscripts.com/open-source/support-us).

We highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using. You'll find our address on [our contact page](https://draftscripts.com/about-us). We publish all received postcards on [our virtual postcard wall](https://draftscripts.com/open-source/postcards).

## Installation

You can install the package via composer:

```bash
composer require draftscripts/permission
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="lara-permission-migrations"
php artisan migrate
```

You can publish the config file with (Optional):

```bash
php artisan vendor:publish --tag="lara-permission-config"
```

now you can visit permission route [/permission]


Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="laravel-openai-views"
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
