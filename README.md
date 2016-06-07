# nhieu-php

A very simple helper library for pluralizing Vietnamese.

## Installation

Via Composer:

```
$ composer require petehouston/nhieu-php
```

## Usage

Make sure to include the `autoload.php`:

```php
require 'vendor/autoload.php';
```

Just call a simple function `nhieu($word, $count = 11)`:

```php
nhieu("xe", 0); // không xe

nhieu("ô tô", 2); // hai ô tô

nhieu("cái bánh", 8); // tám cái bánh

nhieu("người"); // nhiều người

nhieu("lập trình viên", -100); // không lập trình viên
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.