---
title: Testbench Change Log
---

## Version 2.2 {#v2-2}

### v2.2.0 {#v2-2}

* Bump minimum version to PHP v5.4.0.
* Add support for Laravel Framework v4.2.
* Refactor `Orchestra\Testbench\TestCase` bootstrapping process to utilize trait.
* Add `Orchestra\Testbench\TestCaseInterface` and remove dependencies to require `Illuminate\Foundation\Testing\TestCase`.

## Version 2.1 {#v2-1}

### v2.1.2@dev {#v2-1-2}

* Implement [PSR-4](https://github.com/php-fig/fig-standards/blob/master/proposed/psr-4-autoloader/psr-4-autoloader.md) autoloading structure.

### v2.1.1 {#v2-1-1}

* Fixes `Cannot redeclare crypt_random_string()` issue when developing with workbench.

### v2.1.0 {#v2-1-0}

* Update Laravel 4.1 Service Providers.

## Version 2.0 {#v2-0}

### v2.0.6 {#v2-0-6}

* Implement [PSR-2](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md) coding standard.
* Add multiple test case examples.

### v2.0.5 {#v2-0-5}

* Fixed stricter SQLite configuration introduced in Laravel Framework 4.0.8.

### v2.0.4 {#v2-0-4}

* Add migration testcase example.
* Add `Orchestra\Testbench\TestCase::getEnvironmentSetUp()`.

### v2.0.3 {#v2-0-3}

* Fixed a bug when calling `Artisan::call()` from test suite.

### v2.0.2 {#v2-0-2}

* Add unit testing and code coverage.

### v2.0.1 {#v2-0-1}

* Improved performance by reducing registered service providers.

### v2.0.0 {#v2-0-0}

* Initial release.
