## Nova Toggle Switch Field

A Laravel Nova toggle switch field
## Installation

You can install the package in to a Laravel app that uses Nova via composer:

```bash
composer require naif/toggle
```

## Usage:
Add the below to Nova/User.php resource:

```php

Toggle::make('Toggle')->color('green'),

# You can choose a color from one of the below:
- green
- blue
- cyan
- red
- orange

Or you can just put the color's code
Toggle::make('Toggle')->color('#7e3d2f'),
         
```

<img src="https://github.com/naifalshaye/toggle-switch/blob/master/screenshots/colors.png" width="142">

<img src="https://raw.githubusercontent.com/naifalshaye/toggle-switch/master/screenshots/image1.png" width="500">

<img src="https://raw.githubusercontent.com/naifalshaye/toggle-switch/master/screenshots/image2.png" width="500">

<img src="https://raw.githubusercontent.com/naifalshaye/toggle-switch/master/screenshots/image3.png" width="500">

<img src="https://raw.githubusercontent.com/naifalshaye/toggle-switch/master/screenshots/image4.png" width="500">


## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
