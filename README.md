# Export/Import Tool for OpenCart (Russian Edition)

The import / export tool allows an admin user to bulk export categories, products, options, attributes, filters, and customers to an Excel spreadsheet file.
The spreadsheet file can be edited offline and then re-imported into the OpenCart database.

Features include:

- The import can be incremental, that is, the data is updated or added to the OpenCart server.
- Or it may not be incremental, which means that all old data is deleted first before importing.
- Exports can be limited to certain data ranges for products and categories only.
- Multiple languages ​​are also supported.

## Requirements and restrictions

Memory requirements can be quite high.

* Not every shared web hosting account supports high memory usage by processes.
* Therefore, if you are using a basic shared web hosting account, you can export or import no more than a few thousand items at a time.
* Use a dedicated web hosting account if more products need to be processed at one time. Or export and import several times in smaller batches.


## Installation

In your OpenCart admin panel, do the following:

1. Go to `Extensions> Extension Installer`.
2. Download `export-import-tool-3x.ocmod.zip`.
3. Go to `Extensions> Mods`. You should see an entry for this Export / Import Tool.
4. Click the Refresh button (top right of the page).
5. Go to `System> Users> User Group> Change Administrator`.
6. Set access and change permissions for `extension / export_import`.

You should now see the Export / Import tool under System> Tools>> Export / Import.

### Additional help and customized versions

This tool has been successfully tested on standard OpenCart 3.x versions.
Do not use other versions of Opencart with this module.

### Original extension

This extension is based on the [Export / Import Tool] (https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=17). Official site of the author [J.Neuhoff] (https://www.mhccorp.com/)

## License
This Export / Import Tool (c) 2020-2021 is copyright ruOpenCart and is provided under the terms of the [GNU General Public License version 3] (http://www.gnu.org/licenses/gpl.html).

## Support
You can get support on the [forum] (https://forum.opencart.name/). 
