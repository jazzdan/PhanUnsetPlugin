# PhanUnsetPlugin

Intrinsics, such as `unset` look like functions, but they are really expressions disguised as functions. You can pass undefined variables, etc.

There's no reason to use `unset`. You can just set the variable to `null` to achieve the same effect.

# Installation
1. Add `"jazzdan/phan-unset-plugin"` to your `composer.json` file.
2. `composer update && composer install`
3. Add an entry `'vendor/jazzdan/phan-unset-plugin/src/UnsetPlugin.php',` to your phan config file's plugins array stanza.
