# Nexylan Coding Standard

The Nexylan Coding Standard is a set of configurations for many CS tools.

## PHP_CodeSniffer (PHP)

Nexylan Coding Standard is based on PSR and
[Symfony](https://symfony.com/doc/current/contributing/code/standards.html) 
standards plus some rules from
[Slevomat Coding Standard](https://github.com/slevomat/coding-standard).

### Usage

Install it globally with php-code-sniffer (RECOMMENDED):

```bash
composer global require nexylan/coding-standard
```

Or, as a dependency of your project:

```bash
composer require --dev nexylan/coding-standard
```

Then add the standard on your `ruleset.xml` file:

```xml
<?xml version="1.0"?>
<ruleset name="My project standard">
    <rule ref="Nexylan"/>
</ruleset>
```

This is the quickest way, but you can of course personalize or disable some rules.
