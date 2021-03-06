### Work in progress, do not include this package in your project yet...

# Manage newsletters in Laravel 5
[![Latest Version](https://img.shields.io/github/release/freekmurze/laravel-newsletter.svg?style=flat-square)](https://github.com/freekmurze/laravel-newsletter/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/freekmurze/laravel-newsletter/master.svg?style=flat-square)](https://travis-ci.org/freekmurze/laravel-newsletter)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/10993a65-449a-488a-886c-f810b9950070/mini.png)](https://insight.sensiolabs.com/projects/10993a65-449a-488a-886c-f810b9950070)
[![Quality Score](https://img.shields.io/scrutinizer/g/freekmurze/laravel-newsletter.svg?style=flat-square)](https://scrutinizer-ci.com/g/freekmurze/laravel-newsletter)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/laravel-newsletter.svg?style=flat-square)](https://packagist.org/packages/spatie/laravel-newsletter)

This package provides an easy way to manages newsletters.

## Installation

You can install this package via composer using:

```bash
composer require spatie/laravel-newsletter
```

You must also install this service provider.

```php

// config/app.php

'providers' => [
    ...
    'Spatie\Newsletter\NewsletterServiceProvider',
    ...
];
```

If you want to make use of the facade you must install it as well.

```php
// config/app.php
'aliases' => [
    ...
    'Newsltter' => 'Spatie\Newsletter\NewsletterFacade',
];
```

To publish the config file to ``app/config/laravel-newsletter.php`` run:

``` bash
php artisan vendor:publish --provider="Spatie\Newsletter\NewsletterServiceProvider"
```

## Usage

## Testing

``` bash
$ phpunit
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email freek@spatie.be instead of using the issue tracker.

## Credits

- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

This package was inspired by the [Bulk Email Notifications series on Laracasts](https://laracasts.com/lessons/bulk-email-notifications-part-1).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
