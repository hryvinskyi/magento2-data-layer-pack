# GA4 Data Layer for Magento 2

Metapackage that installs every GA4 Data Layer module: GA4 ecommerce events for Google Tag Manager or gtag.js, optional server-side delivery through the GA4 Measurement Protocol or a server-side Tag Manager, and a setup wizard.

```bash
composer require hryvinskyi/magento2-data-layer-pack
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento cache:flush
```

The user guide is in [`docs/ga4-data-layer-guide.md`](https://github.com/hryvinskyi/magento2-data-layer/blob/main/docs/ga4-data-layer-guide.md) of `hryvinskyi/magento2-data-layer`.
