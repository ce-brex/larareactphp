# LaraReactPHP

## About

LaraReactPHP is a Laravel package for using ReactPHP to serve your application.

It's designed for use in a containerised environment, but works well with Supervisor too.

## Requirements

* PHP >= 7.0
* Laravel >= 5.5

## Installation

```
composer require tyea/larareactphp
```

## Usage

```
php artisan serve:reactphp
```

## Performance

| Command                    | Total Wall Clock Time |
| -------------------------- | --------------------- |
| php artisan serve          | 0.2s                  |
| php artisan serve:reactphp | 0.6s                  |

## History

This repo is forked from:

* [mnvx/laravel-reactphp](https://github.com/mnvx/laravel-reactphp)
* [Saoneth/laravel-reactphp](https://github.com/Saoneth/laravel-reactphp)
* [rayout/laravel-reactphp](https://github.com/rayout/laravel-reactphp)
* [nazo/laravel-reactphp](https://github.com/nazo/laravel-reactphp)

## Author

Written by Tom Yeadon in March 2020.
