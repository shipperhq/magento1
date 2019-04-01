# ShipperHQ Migration Tool

Migrate your WebShopApps product configuration to ShipperHQ product configuration for Magento 1.x

## Description

The ShipperHQ Migration Tool will assist you in moving from WebShopApps stand-alone extensions to ShipperHQ. This tool will automatically migrate your product configuration (i.e. attribute values) you  have used with WebShopApps extensions to ShipperHQ product configuration. 

For example, if you have been using Dropship from WebShopApps and are moving to ShipperHQ, you can use the Migration Manager so that all products previously assigned to a warehouse will be assigned to a ShipperHQ Origin (warehouse) you choose.

The Migration Manager tool currently supports migration from

- Dropship
- Product Matrix
- Shipping Override
- Freight modules

If there are other extensions you wish to use this tool with, please let us know.

## Compatibility

- Magento >= 1.7
Note this migration tool is only applicable to Magento 1.x platform

## Installation Instructions

Install using git by cloning this repository to your environment or install manually via a zip file

1. Unzip file  
2. copy contents of src directory to your installation (merge app folders)
3. Refresh the cache and recompile (if using compilation)

## Documentation

Documentation is available on our [Knowledgebase](https://docs.shipperhq.com/migrating-attribute-values-webshopapps-extensions-shipperhq-magento1/)

## Limitations

1. The migration tool does not support multi-select attribute values. For example, if you have products with multiple warehouses selected in dropship, we cannot migrate this to multiple selected values for ShipperHQ origins

## Support

If you have any issues with this extension you can contact us via email at support@shipperhq.com or via our website https://shipperhq.com/contact

## License

See license files

## Copyright

Copyright (c) 2015 Zowta LLC <http://www.ShipperHQ.com>
