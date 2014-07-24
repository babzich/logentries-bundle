# BabLogentriesBundle

A simple wrapper for [logentries/logentries-monolog-handler][1].

## Installation

Download the bundle using composer and run `composer update`

```json
{
    "require": {
        "babzich/logentries-bundle": "0.1"
    }
}
```

## Enable the bundle

Enable the bundle in the kernel:

```php
<?php
// app/AppKernel.php

public function registerBundles()
{
    $bundles = array(
        // ...
        new Bab\LogentriesBundle\BabLogentriesBundle(),
    );
}
```

[1]: https://github.com/logentries/logentries-monolog-handler