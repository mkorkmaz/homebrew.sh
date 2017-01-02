# Homebrew.sh

Batch operations using Homebrew for Mac

- Install PHP 5.6, 7.0 and 7.1, basic extensions and some useful tools using [Homebrew](http://brew.sh)
- Update all PHP versions without interruptions  and cleanup old packages
- Remove all PHP related packages


### Installation
```
$ cd path/to/homebrew.sh/installation/dir
$ git clone https://github.com/mkorkmaz/homebrew.sh.git mybrew
$ chmod u+rwx ./mybrew/brew*
```


### Example Usage
```
$ cd path/to/mybrew/dir
$ ./brew-install-php
$ ./brew-update-php
$ ./brew-remove-php
```

##### Important note:
PHP 5.6 active support date expired. You may need it to run legacy scripts. [See PHP Supported Versions page](http://php.net/supported-versions.php).