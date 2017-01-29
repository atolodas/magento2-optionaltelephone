Zorn_OptionalTelephone
===================
OptionalTelephone removes the telephone requirement in Magento 2 

When uninstalled the requirement will be re-established.

Installation
------------

### Via composer

Please go to the Magento2 root directory and run the following commands in the shell:

```
composer config repositories.zorn_optionaltelephone vcs git@github.com:zsoerenm/magento2-optionaltelephone.git
composer require zsoerenm/magento2-optionaltelephone:dev-master
bin/magento module:enable Zorn_OptionalTelephone
bin/magento setup:upgrade
```

Uninstall
------------

```
bin/magento module:uninstall Zorn_OptionalTelephone
bin/magento setup:upgrade
```

Support
-------
If you encounter any problems or bugs, please create an issue on [GitHub](https://github.com/zsoerenm/magento2-optionaltelephone/issues).


Licence
-------
[GNU General Public License, version 3 (GPLv3)](http://opensource.org/licenses/gpl-3.0)

Copyright
---------
(c) 2017 Sören Zorn