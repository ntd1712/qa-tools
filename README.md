# Common PHP QA tools

Included in this repository are:

* [friendsofphp/php-cs-fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) A tool to automatically fix PHP code style.
* [phpmd/phpmd](https://github.com/phpmd/phpmd) A spin-off project of PHP Depend and aims to be a PHP equivalent of the well known Java tool PMD.
* [phpmetrics/phpmetrics](https://github.com/phpmetrics/PhpMetrics) Static analyzer tool for PHP.
* [phpstan/phpstan](https://github.com/phpstan/phpstan) PHP Static Analysis Tool.
* [sebastian/phpcpd](https://github.com/sebastianbergmann/phpcpd) Copy/Paste Detector (CPD) for PHP code.
* [squizlabs/php_codesniffer](https://github.com/squizlabs/PHP_CodeSniffer) Tokenizes PHP, JavaScript and CSS files and detects violations of a defined set of coding standards.
* [vimeo/psalm](https://github.com/vimeo/psalm) A static analysis tool for finding errors in PHP applications.

## Installation

#### Library

```bash
git clone https://github.com/ntd1712/qa-tools.git
```

#### Composer

This can be installed with [Composer](https://getcomposer.org/doc/00-intro.md)

Define the following requirement in your `composer.json` file.

```json
    {
        "require": {
            "chaos/tools": "*"
        },
    
        "repositories": [
          {
            "type": "vcs",
            "url": "https://github.com/ntd1712/qa-tools"
          }
        ]
    }
```

#### Config

```bash
cp vendor/chaos/tools/.php_cs .
cp vendor/chaos/tools/phpcs.xml .
cp vendor/chaos/tools/phpmd.xml .
cp vendor/chaos/tools/phpstan.neon .
cp vendor/chaos/tools/psalm.xml .
```
