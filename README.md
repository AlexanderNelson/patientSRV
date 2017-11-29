
PatientSRV
==========

A PHP based patient info, invoicing and appointment project using CakePHP. Currently running on apache for healthcare interests and easily adapted to other needs with modification or addition of forms and tables.


[![Build status][shield-build]](#)
[![Dependencies][shield-dependencies]](#)


Table of Contents
-----------------

  * [Requirements](#requirements)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [Support](#support)
  * [License](#license)


Requirements
------------

PatientSRV requires the following to run:

  * app.php file 
  * database
  * server


Usage
-----

Replace all images in image folder and update code in default.ctp to change branding.

#### User:

Obtain login name (email) and create password.

Add information as needed.

#### Admin:

Setup Mysql Database

Enter Password and Login in app.php

Apply to functional business needs and update styling.


Contributing
------------

To contribute, clone this repo locally and commit your code on a separate branch. Please test and format before opening a pull-request:


Support
---------------------

Email: AmVetServ@gmail.com


License
-------

Copyright &copy; 2017, Alexander Nelson



[shield-dependencies]: https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg
[shield-build]: https://img.shields.io/badge/build-passing-brightgreen.svg


# CakePHP Application Skeleton

[![Build Status](https://img.shields.io/travis/cakephp/app/master.svg?style=flat-square)](https://travis-ci.org/cakephp/app)
[![License](https://img.shields.io/packagist/l/cakephp/app.svg?style=flat-square)](https://packagist.org/packages/cakephp/app)

A skeleton for creating applications with [CakePHP](https://cakephp.org) 3.x.

The framework source code can be found here: [cakephp/cakephp](https://github.com/cakephp/cakephp).

## Installation

1. Download [Composer](https://getcomposer.org/doc/00-intro.md) or update `composer self-update`.
2. Run `php composer.phar create-project --prefer-dist cakephp/app [app_name]`.

If Composer is installed globally, run

```bash
composer create-project --prefer-dist cakephp/app
```

In case you want to use a custom app dir name (e.g. `/myapp/`):

```bash
composer create-project --prefer-dist cakephp/app myapp
```

You can now either use your machine's webserver to view the default home page, or start
up the built-in webserver with:

```bash
bin/cake server -p 8765
```

Then visit `http://localhost:8765` to see the welcome page.

## Update

Since this skeleton is a starting point for your application and various files
would have been modified as per your needs, there isn't a way to provide
automated upgrades, so you have to do any updates manually.

## Configuration

Read and edit `config/app.php` and setup the `'Datasources'` and any other
configuration relevant for your application.

## Layout

The app skeleton uses a subset of [Foundation](http://foundation.zurb.com/) CSS
framework by default. You can, however, replace it with any other library or
custom styles.
