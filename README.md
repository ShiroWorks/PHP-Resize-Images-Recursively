## Usage

Put images inside `images` folder and run `php index.php` from the
project's root directory.

If you want to integrate this into your project use class ImageResize

```php
$resizer = new ImageResize();
$resizer->resizeAllImages('directory under which you want to resize');
```
