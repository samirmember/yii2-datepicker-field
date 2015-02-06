# yii2-datepicker-field
The Yii2 Datepicker Field is a simple wrapper for the <a href="https://github.com/kartik-v/yii2-widget-datepicker">Yii2 Widget DatePicker</a> extension.
It simplify the use of the datepicker fields

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

To install, either run

```
$ php composer.phar require samirmember/yii2-datepicker-field "*"
```

or add

```
"samirmember/yii2-datepicker-field": "*"
```

to the ```require``` section of your `composer.json` file.


## Usage

```php
use samirmember\helpers\DatePicker;

  $form->field($model, 'my_date_attribute')->widget(DatePicker::classname());
```

## License

**yii2-datepicker-field** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.
