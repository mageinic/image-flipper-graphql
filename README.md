# Image Flipper GraphQL

**Image Flipper GraphQL is a part of MageINIC Image Flipper extension that adds GraphQL features.** This extension extends Image Flipper definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/imageflippergraphql

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Image Flipper GraphQL requires installing [MageINIC Image Flipper](https://github.com/mageinic/Image-Flipper) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/imageflipper
```

## 2. How to use

- To view the queries that the **MageINIC Image Flipper GraphQL** extension supports, you can check `Image Flipper GraphQl User Guide.pdf` Or run `ImageFlipperGraphQl.postman_collection.json` in Postman.

## 3. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
