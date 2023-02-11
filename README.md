# Greek language pack for [Flarum](https://flarum.org/)

[![Latest Stable Version](https://img.shields.io/packagist/v/flarum-lang/greek?color=success&label=stable)](https://packagist.org/packages/flarum-lang/greek) 
[![Latest Unstable Version](https://img.shields.io/packagist/v/flarum-lang/greek?include_prereleases&label=unstable)](https://packagist.org/packages/flarum-lang/greek) 
[![License](https://img.shields.io/packagist/l/flarum-lang/greek)](https://packagist.org/packages/flarum-lang/greek) 
[![Total Downloads](https://img.shields.io/packagist/dt/flarum-lang/greek)](https://packagist.org/packages/flarum-lang/greek/stats) 
[![Monthly Downloads](https://img.shields.io/packagist/dm/flarum-lang/greek)](https://packagist.org/packages/flarum-lang/greek/stats) 

This language pack contains Greek translations for Flarum (compatible with `1.5.0` or newer) and popular extensions. Full list of supported extensions is available below.


## Installation

You can install language pack using [Composer](https://getcomposer.org/):

```console
composer require flarum-lang/greek
```

Then enable extension in admin panel of your Flarum.


## Updating

You can update language pack using [Composer](https://getcomposer.org/):

```console
composer update flarum-lang/greek
```

Then clear the cache:

```console
php flarum cache:clear
```

## Contributing

All translations are managed on this [Weblate instance](https://weblate.rob006.net/engage/flarum/el/), no coding skills or Git knowledge is required to contribute. Flarum internal strings are handled in the 'core' component, otherwise select the extension you want to translate. You can use the search function on a components page to quickly find specific strings you wish to translate or update.

**Additions and improvements to the translations are very welcome, all help is greatly appreciated!**


## Translation status for Flarum core

| Component | Status |
| --- | --- |
| [Core](https://github.com/flarum/flarum-core) | [![Translation status](https://weblate.rob006.net/widgets/flarum/el/core/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/core/el/) |
| Validation | [![Translation status](https://weblate.rob006.net/widgets/flarum/el/validation/svg-badge.svg)](https://weblate.rob006.net/projects/flarum/validation/el/) |


## Translation status for official extensions

<!-- flarum-extensions-list-start -->
<!-- flarum-extensions-list-stop -->


## Translation status for Friends of Flarum extensions

<!-- fof-extensions-list-start -->
<!-- fof-extensions-list-stop -->


## Translation status for community extensions

<!-- various-extensions-list-start -->
<!-- various-extensions-list-stop -->


## Translation status for premium extensions

<!-- premium-extensions-list-start -->
<!-- premium-extensions-list-stop -->


## Credits

This language pack is part of [Flarum translations collective](https://github.com/rob006-software/flarum-translations).

Translation for Day.js comes from the [source](https://github.com/iamkun/dayjs/blob/v1.10.4/src/locale/el.js).

Translation for `validation.yml` is based on [Laravel translations](https://github.com/Laravel-Lang/lang/blob/8.1.3/src/el/validation.php).
