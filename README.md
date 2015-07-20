yii2-gravatar
=============

Gravatar Widget for Yii Framework 2

How to install?
---------------

Get it via [composer](http://getcomposer.org/) by adding the package to your `composer.json`:

```json
{
  "require": {
    "cebe/yii2-gravatar": "*"
  }
}
```

or running command line:

```php
php composer.phar require cebe/yii2-gravatar "*"
```

Alternatively just run `composer require cebe/yii2-gravatar`.

You may also check the package information on [packagist](https://packagist.org/packages/cebe/yii2-gravatar).

Usage
-----

```php
<?= \cebe\gravatar\Gravatar::widget([
    'email' => 'mail@cebe.cc',
    'options' => [
        'alt' => 'Carsten Brandt'
    ],
    'size' => 32
]) ?>
```
