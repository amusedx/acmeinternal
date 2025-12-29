# acme/internal-utils

A minimal Composer package that prints **Hello World**.

## Installation
```bash
composer require acme/internal-utils
```

## Usage
```php
<?php
require 'vendor/autoload.php';

use Acme\InternalUtils\Utils;

Utils::hello();
```

Output:
```
Hello World
```

## License
MIT
