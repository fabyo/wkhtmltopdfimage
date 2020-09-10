# wkhtmltopdfimage
This repository contains the static compiled binaries linux from the wkhtmltopdf and wkhtmltoimage project. More about the functionality of wkhtmltopdf and wkthmltoimage can be found there.

# wkhtmltopdf 0.12.6
https://wkhtmltopdf.org/downloads.html

# Installation
composer require fabyo/wkhtmltopdfimage

The binary will then be located at:

vendor/fabyo/wkhtmltopdfimage/bin

Move the binaries to a path that is not in a synced folder, for example:
cp vendor/h4cc/wkhtmltopdfimage/bin/wkhtmltopdf /usr/local/bin/
cp vendor/fabyo/wkhtmltopdfimage/bin/wkhtmltoimage /usr/local/bin/

and make it executable:

chmod +x /usr/local/bin/wkhtmltopdf
chmod +x /usr/local/bin/wkhtmltoimage
