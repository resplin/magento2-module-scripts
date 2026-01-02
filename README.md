# magento2-module-scripts
Helpful scripts for Magento2

### mage-clean
- Enables maintenance mode
- Removes generated folders
- Clears the cache
- Runs setup:upgrade and setup:di:compile
- Redeploys static content
- Disables maintenance mode

### mage-init

### mage-refresh-composer
- Remove vendor/
- Reinstalls packages via `composer install`
- Runs `mage-clean`
- Fixes .htaccess 'SymLinks' directive

### mage-unzip
- Extracts tarballs for app, dev, generated, lib, and vendor

### mage-zip
- Creates tarballs for app, dev, generated, lib, and vendor
