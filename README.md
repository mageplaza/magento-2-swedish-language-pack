## Magento 2 Swedish Language Pack

For better assistance, Mageplaza makes an effort to create **Magento 2 Swedish Language Pack** for everyone who needs. The topic provides a package of free guides in order to apply the Swedish dictionary on your online store. Why do we want to recommend this topic? In fact, the approaching to other countries is the desired development of each shop. In case that you have the plan to do business in Sweden, it is appropriate to use the native language - Swedish for all transactions.

By following Swedish Language Pack tutorial, there is no need to copy all CSV file or any manual activity. The translation is directly connected with the data of Magento 2 Translation Project at Crowdin and then automatically completed after selecting *Swedish (Sweden)* locale option.

Read more [Magento 2 Swedish Language Pack](https://www.mageplaza.com/magento-2-swedish-language-pack.html)


## Overview

- Download & Contribute
- Install Swedish Language Pack
- How to Install Swedish Language Pack

## Download & Contribute to Swedish Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Swedish Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-swedish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-swedish-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/sv_SE.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Swedish Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Swedish language pack via composer is never easier.

**Install Swedish pack**:

```
composer require mageplaza/magento-2-swedish-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy sv_SE

```


**Update  Swedish pack**:

```
composer update mageplaza/magento-2-swedish-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy sv_SE

```

#### Authentication required (Optional)

[Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Swedish language pack
- Step 2: Unzip Swedish pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Swedish language pack

You can download the language pack from above link

#### Step 2: Unzip Swedish pack

Unzip the Swedish language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Swedish pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-swedish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-swedish-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `sv_SE.zip` into `app/i18n/mageplaza/sv_SE/sv_SE.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Swedish language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Swedish Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/sv_SE

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-swedish-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/