# PHP Ip library

[![Latest Stable Version](https://poser.pugx.org/josantonius/ip/v/stable)](https://packagist.org/packages/josantonius/ip) [![Total Downloads](https://poser.pugx.org/josantonius/ip/downloads)](https://packagist.org/packages/josantonius/ip) [![Latest Unstable Version](https://poser.pugx.org/josantonius/ip/v/unstable)](https://packagist.org/packages/josantonius/ip) [![License](https://poser.pugx.org/josantonius/ip/license)](https://packagist.org/packages/josantonius/ip)

[Versión en español](README-ES.md)

PHP class to get user IP.

---

- [Installation](#installation)
- [Requirements](#requirements)
- [Quick Start and Examples](#quick-start-and-examples)
- [Available Methods](#available-methods)
- [Usage](#usage)
- [Tests](#tests)
- [Contribute](#contribute)
- [Repository](#repository)
- [License](#license)
- [Copyright](#copyright)

---

<p align="center"><strong>Take a look at the code</strong></p>

<p align="center">
  <a href="" title="Take a look at the code">
  	<img src="https://raw.githubusercontent.com/Josantonius/PHP-Algorithm/master/resources/youtube-thumbnail.jpg">
  </a>
</p>

---

### Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

To install PHP Ip library, simply:

    $ composer require Josantonius/Ip

The previous command will only install the necessary files, if you prefer to download the entire source code (including tests, vendor folder, exceptions not used, docs...) you can use:

    $ composer require Josantonius/Ip --prefer-source

Or you can also clone the complete repository with Git:

	$ git clone https://github.com/Josantonius/PHP-Ip.git

### Requirements

This library is supported by PHP versions 5.6 or higher and is compatible with HHVM versions 3.0 or higher.

### Quick Start and Examples

To use this class, simply:

```php
require __DIR__ . '/vendor/autoload.php';

use Josantonius\Ip\Ip;
```
### Available Methods

Available methods in this library:

```php
Ip::get();
```
### Usage

Example of use for this library:

```php
<?php
require __DIR__ . '/vendor/autoload.php';

use Josantonius\Ip\Ip;

print_r(Ip::get()); # 66.249.76.29
```

### Tests 

To use the [test](tests) class, simply:

```php
<?php
$loader = require __DIR__ . '/vendor/autoload.php';

$loader->addPsr4('Josantonius\\Ip\\Tests\\', __DIR__ . '/vendor/josantonius/ip/tests');

use Josantonius\Ip\Tests\IpTest;

```
Available test methods in this library:

```php
IpTest::testGetIp();
```

### Contribute
1. Check for open issues or open a new issue to start a discussion around a bug or feature.
1. Fork the repository on GitHub to start making your changes.
1. Write one or more tests for the new feature or that expose the bug.
1. Make code changes to implement the feature or fix the bug.
1. Send a pull request to get your changes merged and published.

This is intended for large and long-lived objects.

### Repository

All files in this repository were created and uploaded automatically with [Reposgit Creator](https://github.com/Josantonius/BASH-Reposgit).

### License

This project is licensed under **MIT license**. See the [LICENSE](LICENSE) file for more info.

### Copyright

2017 Josantonius, [josantonius.com](https://josantonius.com/)

If you find it useful, let me know :wink:

You can contact me on [Twitter](https://twitter.com/Josantonius) or through my [email](mailto:hello@josantonius.com).
