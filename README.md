yii2-gravatar
=============

Gravatar Widget for Yii Framework 2

How to install?
---------------

Get it via [composer](http://getcomposer.org/) by adding the package to your `composer.json`:

```json
{
  "require": {
    "cebe/yii2-gravatar": "^1.0"
  }
}
```

Alternatively just run `composer require cebe/yii2-gravatar`.

You may also check the package information on [packagist](https://packagist.org/packages/cebe/yii2-gravatar)
and follow the [extension page on yiiframework.com](https://www.yiiframework.com/extension/cebe/yii2-gravatar) for udpates.

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
