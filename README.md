# CKEditor 4.22.1 Custom Version

This repository contains a customized version of CKEditor 4.22.1.

## Source and Modifications

- **Source**: This package was downloaded from the official CKEditor website at [CKEditor 4 Download](https://ckeditor.com/ckeditor-4/download/#ckeditor-4).
- **Package**: Full Package, which includes a heavier preset with a multiline toolbar and 72 plugins.
- **Download URL**: The original zip file was downloaded from [CKEditor 4.22.1 Full Package](https://download.cksource.com/CKEditor/CKEditor/CKEditor%204.22.1/ckeditor_4.22.1_full.zip).
- **Modification**: After extracting the package, we modified `ckeditor.js` to disable the version check by setting `config.versionCheck` to `!1`.

## License

This software is licensed under the Mozilla Public License Version 1.1 or later. For more details, see the `LICENSE.md` file.

## Change Log

For a detailed list of changes, see [CHANGES.md](./CHANGES.md).

## Contact

For any questions or concerns, please contact us at [info@dlyog.com](mailto:info@dlyog.com).

---

# CKEditor 4

Copyright (c) 2003-2023, CKSource Holding sp. z o.o. All rights reserved.  
https://ckeditor.com - See https://ckeditor.com/legal/ckeditor-oss-license for license information.

CKEditor 4 is a text editor to be used inside web pages. It's not a replacement
for desktop text editors like Word or OpenOffice, but a component to be used as
part of web applications and websites.

## Documentation

The full editor documentation is available online at the following address:  
https://ckeditor.com/docs/

## Installation

Installing CKEditor is an easy task. Just follow these simple steps:

1. **Download** the latest version from the CKEditor website:  
   https://ckeditor.com. You should have already completed this step, but be
   sure you have the very latest version.
2. **Extract** (decompress) the downloaded file into the root of your website.

**Note:** CKEditor is by default installed in the `ckeditor` folder. You can
place the files in whichever you want though.

## Checking Your Installation

The editor comes with a few sample pages that can be used to verify that
installation proceeded properly. Take a look at the `samples` directory.

To test your installation, just call the following page at your website:

    http://<your site>/<CKEditor installation path>/samples/index.html

For example:

    http://www.example.com/ckeditor/samples/index.html
