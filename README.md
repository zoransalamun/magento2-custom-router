# magento2-custom-router
Example router in Magento 2.

<h2>Install:</h2>
First add repository to composer configuration:
```bash
composer config repositories.inchoocustomrouter vcs git@github.com:zoransalamun/magento2-custom-router.git
```
Require new package with composer:
```bash
composer require inchoo/custom-router:dev-master
```
Enable Inchoo CustomRouter module
```bash
php bin/magento module:enable Inchoo_CustomRouter
```

Flush everything:
```bash
php bin/magento setup:upgrade
```
