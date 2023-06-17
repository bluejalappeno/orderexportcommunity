## BLUEJALAPPENO ORDER EXPORT COMMUNITY
Order Export Extension for Magento 1

## Description

Export full order, customer and item information in a variety of export formats.
 
Order Export Community (free) supports 3 types of exports:
- Standard csv file - Exports orders including product details with one line item per row
- Sage 50 Accounts export - Allows you to export orders in a "transaction" format so you can import transactions only into Sage 50 Accounts (note this is not an itemised export)
- HighRise export - Allows you to export order information directly into your Highrise CRM


## Installation

Please follow these instructions exactly as written in order, step by step, or you could see issues that will take some time to resolve.
 
WARNING: We recommend you backup your Magento installation and database immediately prior to installing any extension. We do not take any responsibility for this may cause. We also recommend you install and test on a non-business critical environment e.g. development prior to deploying to your live site
1. Switch off the compiler under System > Tools > Compilation
2. Ensure the cache is switched on under System > Cache Management
3. After downloading the extension zip file, unzip to a local directory.
4. Copy the 'app' directory from 'src' onto your base Magento installation, overwriting all files. 5. Note - this will not replace any core Magento files.
5. If the zip contains 'app/design/frontend', ensure these files are merged into your theme
6. If the zip contains 'app/design/adminhtml', ensure these files are merged into your theme
7. If the zip contains a skin folder, ensure these files are merged into your theme
8. Log out of your Magento admin and log in again
9. Disable the cache
10. Flush the cache or delete contents of var/cache and var/session
11. Open the frontend of your site to force the new extension to load
12. If you are using the compiler, recompile from System > Tools > Compilation
13. Re-index all of your data under System > Index Management
14. Enable the cache under System > Cache Management
15. From here, follow the instructions for your specific extension.

## Configuration

See WIKI http://wiki.bluejalappeno.com/home/order-export/order-export-configuration#TOC-Installation1

## Support

If you have any issues, please raise a Github issue. Alternatively you can email sales@bluejalappeno.com. As this is a free extension, we do not guarantee support or SLA. 

## Contribution

Any contribution is highly appreciated. The best way to contribute code is to open a pull request on GitHub.

## License

See license files

## Copyright

Copyright (c) 2012 Wimbolt Ltd (http://www.bluejalappeno.com)