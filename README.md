SMS Gateway API Client
======================

This is a PHP client for sending SMS messages using the SMS Gateway Hub API.

Requirements
------------

* PHP 7.2 or higher
* `curl` extension

Configuration
-------------

Create a `config.php` file with the following settings:

```php
<?php
return [
    'apikey' => 'YourAPIkey',
    'apisender' => 'TESTIN',
    'route' => 1,
    'channel' => 2,
    'DCS' => 0,
    'flashsms' => 0,
];
