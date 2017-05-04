# Kirby-ref

This is wrapper of excelent little library [php-ref](https://github.com/digitalnature/php-ref). Packaged as kirby plugin. All credit goes to @digitalnature>



Php-ref is alternative to ```print_r()``` and ```var_dump()```.




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
You can download the latest version of the plugin from https://github.com/floriankarsten/kirby-ref/releaseslatest

### With Git
If you are familiar with Git, you can clone this repository from Github into your plugins folder.

```git clone https://github.com/floriankarsten/kirby-ref/releases.git kirby-ref```


## Usage

Use simply as ```ref($var)``` instead of ```var_dump($var)```