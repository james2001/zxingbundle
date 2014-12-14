Zxing Bundle
============

Call [zxing](https://github.com/zxing/zxing/) (code barre reader) with [Symfony2](http://symfony.com/)

Requirement
-----------

This library package requires PHP 5.3 or later, java, symfony/framework-bundle ~2.1 and james2001/zxing ~1.0


Setup
-----

- With composer *(recommended)*

Add the following line to the `composer.json` of your project and launch composer install command

```json
{
    "require": {
        "james001/zxing-bundle": "~1.0"
    }
}
```

Launch install from your project root with:

```shell
composer install --no-dev --prefer-dist
```

Use
---

```php
$imagePath = '/path/image.jpg';
$myCode = $this->get('james2001.zxing')->findFirst($imagePath);
```


