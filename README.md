# amadeus-ws-client: PHP client for the Amadeus GDS SOAP Web Service interface

[![Build Status](https://travis-ci.org/amabnl/amadeus-ws-client.svg?branch=develop)](https://travis-ci.org/amabnl/amadeus-ws-client) [![Coverage Status](https://coveralls.io/repos/github/amabnl/amadeus-ws-client/badge.svg?branch=develop)](https://coveralls.io/github/amabnl/amadeus-ws-client?branch=develop) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/amabnl/amadeus-ws-client/badges/quality-score.png?b=develop)](https://scrutinizer-ci.com/g/amabnl/amadeus-ws-client/?branch=develop) [![Style Status - PSR-2](https://styleci.io/repos/49078536/shield?branch=develop)](https://styleci.io/repos/49078536)

This client library provides access to the Amadeus GDS SOAP Web Service interface. 

To use this client, you must first obtain your personal access to the Web Service interface through an Amadeus Sales channel of your choice.

The Amadeus documentation portal can be found at https://webservices.amadeus.com/
 
![](http://i.imgur.com/7ZcCgnj.jpg)

# Requirements

* PHP 5.4+
* SOAP and XSL extensions activated
* A WSDL & authentication details from Amadeus _(SoapHeader 4 or SoapHeader 2)_

# Installation

Install amadeus-ws-client through [Composer](http://getcomposer.org).

```bash
composer require amabnl/amadeus-ws-client:dev-master
```

After installing, you need to require Composer's autoloader:

```php
require 'vendor/autoload.php';
```

Update composer to get the client:

 ```bash
composer update
 ```

# Warning: under active development

This library is under active development. The public API's could change any time at the moment!

We will release a 0.1 version when we feel the library is stable enough, after which we will be following semantic versioning.

For now, if you want the bleeding edge, point your composer.json towards `dev-develop`. If you only want what we have verified as working, go for `dev-master`.

# Usage

- [About &amp; Get Started](docs/about-get-started.rst)
- [List of supported messages](docs/list-of-supported-messages.rst)
- [How to](docs/how-to.rst)
- [Examples](docs/samples.rst)

[Changelog](CHANGELOG.md)
