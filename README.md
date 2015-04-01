# PHP_CodeSniffer rules

[![Latest Stable Version](https://poser.pugx.org/jakubzapletal/php_codesniffer-rules/v/stable.png)](https://packagist.org/packages/jakubzapletal/php_codesniffer-rules)
[![Total Downloads](https://poser.pugx.org/jakubzapletal/php_codesniffer-rules/downloads.png)](https://packagist.org/packages/jakubzapletal/php_codesniffer-rules)
[![Latest Unstable Version](https://poser.pugx.org/jakubzapletal/php_codesniffer-rules/v/unstable.png)](https://packagist.org/packages/jakubzapletal/php_codesniffer-rules)
[![License](https://poser.pugx.org/jakubzapletal/php_codesniffer-rules/license.png)](https://packagist.org/packages/jakubzapletal/php_codesniffer-rules)

This is a simple library of modified [PSR](https://github.com/php-fig/fig-standards) rules for [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer).

## Installation

### Composer

If you don't have Composer [install](http://getcomposer.org/doc/00-intro.md#installation) it:

```bash
$ curl -s https://getcomposer.org/installer | php
```

Add `jakubzapletal/php_codesniffer-rules` to `composer.json`:

```bash
$ composer require --dev jakubzapletal/php_codesniffer-rules ~0.1
```


## Usage

### PSR2 without camel case method name

Sometimes is a code convention to write method names by underscore in test classes. In this case you can still keep checking
PSR-2 standard thanks to ruleset below.

```bash
$ vendor/bin/phpcs --standard=vendor/jakubzapletal/php_codesniffer-rules/psr2-without-camel-case-method-name.xml </PATH/TO/TESTED/FOLDER>
```
