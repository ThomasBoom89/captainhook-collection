# Captainhook Collection

![License](https://img.shields.io/badge/license-MIT-green?style=plastic)

A collection of git hooks installed with [CaptainHook](https://github.com/CaptainHookPhp/captainhook).

## Requirements

You need to have php and composer installed.
Obvious, you need CaptainHook installed too and also the specific tool you would like to use as hook.

```zsh
composer require --dev captainhook/captainhook
// For example phpunit
composer require --dev phpunit/phpunit
```

For general installation and usage of CaptainHook see their [docs](https://captainhookphp.github.io/captainhook/).

## Installation

```zsh
composer require --dev thomasboom89/captainhook-collection
```

There is an example config for composer and also an example config for captainhook in
vendor/thomasboom89/captainhook-collection.
You can modify and/or copy specifc parts to your config in your projects root directory.

Don't forget to run

```zsh
vendor/bin/captainhook install
```

to update your git hooks.

## License

Captainhook Collection
\
Copyright (C) 2022 ThomasBoom89. MIT license.
