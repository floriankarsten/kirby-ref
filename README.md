# Kirby-ref

This is wrapper of excelent little library [php-ref](https://github.com/digitalnature/php-ref). Packaged as kirby plugin. All credit goes to @digitalnature.


Php-ref is nice alternative to ```print_r()``` and ```var_dump()```.

![alt text](https://github.com/floriankarsten/kirby-ref/raw/stuff/kirby-ref.gif "Kirby ref GIF")

## Installation
To install the plugin, please put it in the `site/plugins` directory.  
The plugin folder must be named `kirby-ref`.

```
site/plugins/
    kirby-ref/
        kirby-ref.php
        ...
```

### Download
Link to latest version https://github.com/floriankarsten/kirby-ref/releases/latest

### With Kirby CLI
```kirby plugin:install floriankarsten/kirby-ref```

### With Git
```git clone https://github.com/floriankarsten/kirby-ref/releases.git kirby-ref```
You can of course have it as submodule. There won't be many updates.


## Usage

Use simply as ```ref($var)``` instead of ```var_dump($var)```. There is also ```reftext($var)``` which is ref in plain text mode. Both of the functions have different name from original [php-ref](https://github.com/digitalnature/php-ref) because of name collision. Proposals for better function names are welcome. Or just rename it yourself :).
