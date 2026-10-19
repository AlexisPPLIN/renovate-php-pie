# renovate-php-pie

Example repository to test Renovate **PHP PIE** support.

---

## Overview

This is a tiny PHP project that declares both a PHP extension (`ext-xdebug`) and a regular library (`symfony/yaml`). It exists primarily as a test‑bed for Renovate's PHP PIE functionality – i.e. automatically detecting and updating PHP dependencies.

## Requirements

- PHP 8.5 or newer
- PIE : https://github.com/php/pie
- Composer : https://getcomposer.org/

## Installation

```bash
composer install
```

The command resolves the packages listed in `composer.json` and creates the `vendor/` directory.

```bash
pie install
```

The command resolves the `ext-` packages listed in `composer.json` and install the needed PHP extensions using PIE.

## License

The project does not ship a specific license file; it is provided as an example repository.
