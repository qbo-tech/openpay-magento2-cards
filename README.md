Openpay-Magento2-Cards
======================

Openpay payment gateway Magento2 extension


Install
=======

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash    
    composer require qbo/openpay-cards
    ```
   Wait while dependencies are updated.

3. Enter following commands to enable module:

    ```bash
    php bin/magento module:enable Openpay_Cards --clear-static-content
    php bin/magento setup:upgrade
    php bin/magento cache:clean
    ```

4. Enable and configure Openpay in Magento Admin under Stores > Configuration > Sales > Payment Methods > Openpay


