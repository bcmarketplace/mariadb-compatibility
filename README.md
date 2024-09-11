# BCMarketplace_MariaDBCompatibility

**Extension Name**: BCMarketplace     
**Module Name**: BCMarketplace_MariaDBCompatibility 
**Author**: Raphael Baako

## Description ##
This module enhances Magento's compatibility with MariaDB versions ranging from 10.2 to 10.6.

## Compatibility

Supported Magento Versions:

- Magento 2.4.x Open Source/Commerce

## Installation

There are two ways to install the module:

### Install via Composer (preferred)

```bash
composer config repositories.mariadb-compatibility git https://github.com/bcmarketplace/mariadb-compatibility.git
composer require bcmarketpalce/mariadb-compatibility
```

## Documentation

This module overrides the `di.xml` type `Magento\Framework\DB\Adapter\SqlVersionProvider` to include MariaDB version 10.6. No additional configuration is required.

---
