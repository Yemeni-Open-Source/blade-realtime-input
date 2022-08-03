<div style="text-align: center;">

![Packagist Downloads](https://img.shields.io/packagist/dt/yemeni-open-source/blade-realtime-input?color=blue&label=Downloads&logo=packagist&logoColor=white)
![Packagist Version](https://img.shields.io/packagist/v/yemeni-open-source/blade-realtime-input?color=green&label=Version&logo=laravel&logoColor=white)
[![GitHub license](https://img.shields.io/github/license/yemeni-open-source/blade-realtime-input)](https://github.com/yemeni-open-source/blade-realtime-input/blob/main/LICENSE)
</div>

# Laravel Realtime input

Enjoy realtime input validation by passing your rules in your input itself.

## Requirments

This package is tested with Laravel v8 and it should work on Laravel v7 and v9

|||
|-|-|
|php| ^7.4&#124;^8.0|
|Composer| ^2.3|
|Laravel| ^8.0|

## Installation

Install the package by using composer:

> ```composer require yemeni-open-source/blade-realtime-input```

## Basic Usage



```blade
<x-realtime-input::forms.string-input name="username" rules="required|min:5" />
```

## Advance Usage

You can add ```id```, ```class``` and ```type``` to your input like following

```blade
<x-realtime-input::forms.string-input name="username" rules="required|min:5" id="user" class="form-control" />
```


You can add array name like following

```blade
<x-realtime-input::forms.string-input name="username[]" rules="required|min:5" id="user" class="form-control" />
```

## License

The MIT License (MIT). Please see [MIT license](LICENSE) File for more information.