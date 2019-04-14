# Looking for maintainer
These [Magento2Translations](http://magento2translations.github.io/) packages are unmaintained. This means that from time to time we will run the sync and build from Crowdin. But we probably won't add Magento/Crowdin versions. If you would like to continue the work done here please send us a message.

Have a look at all the other great community maintained packages at [e-conomix/magento-translations](https://github.com/e-conomix/magento-translations).
Or [Mageplaza maintained packages](https://github.com/mageplaza?q=language).

# Persian (فارسی) Magento2 Language Pack (fa_IR)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Persian (فارسی) translations used can be found [here](https://crowdin.com/project/magento-2/fa).
This translation is usefull for people living in the Iran (ایران).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [2.2.1](https://crowdin.com/project/magento-2/fa#/2.2.1) at Crowdin and based on the Magento 2.2.1 sourcefiles.
There have been  8508 strings translated of the 8797 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/97)

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_fa_ir:2.2.1-dev
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_fa_ir/archive/2.2.1.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_fa_ir`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/fa_IR/fa_IR.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Persian (Iran)*'

# Contribute
To help push the '*Persian (فارسی) Magento2 Language Pack (fa_IR)*' forward please goto [this](https://crowdin.com/project/magento-2/fa) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).