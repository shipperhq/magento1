# ShipperHQ
Integrate Magento 1 with ShipperHQ to provide highly flexible shipping rate management.
More information on ShipperHQ capabilities are available at www.shipperhq.com

## Facts

- [extension on GitHub](https://github.com/shipperhq/magento1)
- Magento v2.0 available for download from [GitHub](https://github.com/shipperhq/module-shipper)

## Description

ShipperHQ will install as a simple shipping carrier in Magento 1. To get started you'll need to sign up for a ShipperHQ account at [ShipperHQ](https://shipperhq.com).

There's no cost for the extension and ShipperHQ is free for 30 days.

Once installed, you can configure with your ShipperHQ platform credentials to provide multiple carrier rates and manage complex shipping rules via our ShipperHQ dashboard.

## Compatibility

- Magento >= 1.7
- PHP 5.6
- PHP 7.2
- Supports both Magento Opensource (Community) and Magento Enterprise

## Installation Instructions

Install using FTP:

1. Switch off the Magento Compiler if enabled under System->Tools->Compilation
1. Ensure Cache is enabled in Admin under System -> Cache Management
1. Extract all the Zip archive(s)
1. Copy the contents of the app directory from the extracted Zip into your Magento base directory overwriting any files, except for the “etc” directory (which will be copied last). * **Note**: This does not overwrite any core files
1. Copy the contents of the other directories present in the extracted Zip (for example, “lib” and “skin”), except for the “docs” directory (which is documentation only).
1. Copy over the app/etc directory that was omitted in step #4. This greatly reduces the chance of the SQL not running correctly.
1. Log out of admin and back in. If you do not do this you will get 404 Access Denied errors
1. Disable cache in admin
1. Flush the Magento cache storage in cache management by clicking the ‘Flush Magento Cache’ Button. (Or you can manually remove /var/cache and var/session contents.)
1. Open frontend of website to force extension to load (this will ensure that the SQL updates within extension are performed).
1. If you’re using the compiler you need to recompile via System->Tools->Compilation. If you do not you will see an error similar to ‘Call to a member function toOptionArray() on a non-object…’ when accessing shipping methods. You may also see Fatal Errors for missing files
1. You have now installed your extension and should see it present in relevant area of backend
1. Re-enable cache in admin

Further information, troublshooting tips and our post-installation guide is available from [ShipperHQ documentation](https://docs.shipperhq.com/installing-the-shipperhq-magento-extension/)

## Support

If you have any issues with this extension, open an issue on [GitHub](https://github.com/shipperhq/module-shipper/issues).

Alternatively you can contact us via email at support@shipperhq.com or via our website https://shipperhq.com/contact

Contribution
------------
Any contribution is highly appreciated. The best way to contribute code is to open a [pull request on GitHub](https://help.github.com/articles/using-pull-requests).

License
-------
See license files

Copyright
---------
Copyright (c) 2015 Zowta LLC (http://www.ShipperHQ.com)
