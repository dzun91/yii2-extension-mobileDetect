yii2-extension-mobileDetect
===========================

Detect type of device by information from request.
## Notes

This extension based on mobiledetect project http://mobiledetect.net/.

See [here] (https://github.com/serbanghita/Mobile-Detect/) and [here] (http://demo.mobiledetect.net/) for more documentation and examples.

## Usage

Update config file *config/web.php* :

```php
return [
    ...
    'components' => [
        'mobileDetect' => [
            'class' => 'extensions\mobileDetect\Detect',
        ],
    ],
    ...
];
```

Set event handler for detect type of device before run Application
```php
$md = \Yii::$app->mobileDetect;

var_dump($md);
```
