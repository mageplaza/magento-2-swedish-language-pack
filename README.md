## Magento 2 Swedish Language Pack

For better assistance, Mageplaza makes an effort to create **Magento 2 Swedish Language Pack** for everyone who needs. The topic provides a package of free guides in order to apply the Swedish dictionary on your online store. Why do we want to recommend this topic? In fact, the approaching to other countries is the desired development of each shop. In case that you have the plan to do business in Sweden, it is appropriate to use the native language - Swedish for all transactions.

Read more [Magento 2 Swedish Language Pack](https://www.mageplaza.com/magento-2-swedish-language-pack.html)

![Mageplaza Swedish language pack](https://cdn3.mageplaza.com/media/general/qjWPj1W.png)

## Overview

1. Language Package Process
2. Install Swedish Language Pack
3. How to active Swedish language pack
4. How to contribute
5. Supported Magento versions
6. Notes
7. Language package authors

## 1. Language Package Process

This is status of Swedish Language Pack, you can see how many percentage of this project has been done.

![Swedish language pack process](https://progress-bar.dev//?title=completed)

It is not fully translated? Feel free to contribute:
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/mageplaza/magento-2-swedish-language-pack/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


Find other [language packs here](https://www.mageplaza.com/magento-2-extensions/language-packs.html)

## 2. How to Install Swedish Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Swedish language pack via composer is never easier.

**Install Swedish pack**:

With Marketing Automation (recommend):

```
composer require mageplaza/magento-2-swedish-language-pack:dev-master mageplaza/module-smtp 
php bin/magento setup:static-content:deploy sv_SE
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

Without Marketing Automation:

```
composer require mageplaza/magento-2-swedish-language-pack:dev-master
php bin/magento setup:static-content:deploy sv_SE
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```


**Update  Swedish pack**:

```
composer update mageplaza/magento-2-swedish-language-pack:dev-master
php bin/magento setup:static-content:deploy sv_SE
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)

Or use these keys:

```
Public Key: c7af1bfc9352e9c986637eec85ed53af
Private Key: 17e1b72ea5f0b23e9dbfb1f68dc12b53
```



### ✓ Method #2. Copy & Paste method (Not recommended)

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
unzip master.zip app/i18n/Mageplaza/
```

Rename folder `magento-2-swedish-language-pack` to `sv_se`.


You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Swedish pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-swedish-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-swedish-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `master.zip` into `app/i18n/Mageplaza/sv_se/`

See this screenshot:

![Swedish pack](https://cdn3.mageplaza.com/media/general/language-pack.png)

This language pack code is: **sv_se**

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to Active the Swedish language pack 

Now time to active the Swedish language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Swedish language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute

Contribute to this language at :
- [On Crowdin](https://crowdin.com/project/magento-2): It takes time to approve your contribution by Magento team.
- [On Github](https://github.com/mageplaza/magento-2-swedish-language-pack/blob/master/HOW-TO-CONTRIBUTE.md): It's faster, our team will approve it after you send pull request.


## 5. Supported Magento versions

It supports all Magento 2 versions include [Magento 2 open-source](https://www.mageplaza.com/download-magento/) (Community), Magento 2 Commerce (EE), Magento Cloud, Magento B2B, Magento MSI.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x
- Magento v2.3.x
- Magento v2.4.x



## 6. Notes 

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-swedish-language-pack/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Magento Community
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## 8. References 

- https://www.mageplaza.com/magento-2-swedish-language-pack.html
- https://crowdin.com/project/magento-2



## Mageplaza extensions on Magento Marketplace, Github


- [Layered Navigation](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)
- [One Step Checkout](https://marketplace.magento.com/mageplaza-magento-2-one-step-checkout-extension.html)
- [SMTP](https://marketplace.magento.com/mageplaza-module-smtp.html) ; [SMTP on Github](https://github.com/mageplaza/magento-2-smtp)
- [Blog](https://github.com/mageplaza/magento-2-blog)
- [Security](https://marketplace.magento.com/mageplaza-module-security.html)
- [Social Login](https://github.com/mageplaza/magento-2-social-login)
- [SEO](https://github.com/mageplaza/magento-2-seo) ; [SEO on Marketplace](https://marketplace.magento.com/mageplaza-magento-2-seo-extension.html)
- [SMTP](https://github.com/mageplaza/magento-2-smtp)
- [Product Slider](https://github.com/mageplaza/magento-2-product-slider)
- [Banner](https://github.com/mageplaza/magento-2-banner-slider)
- [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)



