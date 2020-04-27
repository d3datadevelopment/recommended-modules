# Recommended Modules (metapackage)
a requirement list of recommended modules for the OXID eShop
contains an additional list of other suggested modules

## Requirements

* OXID eSales eShop Compilation 6.0

## Modules

### require
* Module Internals ~ OXID Community
* OXID Console ~ OXID PS
* OXID Module Configuration Im-/Exporter ~ OXID PS

### require-dev
* D3 Development Tool ~ D3
* OXID-DebugBar ~ FlorianPalme

### suggest list
* D³ Auftragsmanager ~ D3
* Disable Admin Elements ~ D3
* AdminSearch ~ XID Community
* OXID Extended Order Admin ~ OXID Projects
* Facebook Social Plugins ~ OXID Projects
* Lexware Export ~ OXID Projects
* PDF Invoice ~ OXID Projects
* Statistics ~ OXID Projects
* Tags ~ OXID Projects
* Captcha ~ OXID Projects
* PHPMailer Bugfix ~ Vanilla-thunder
* WYSIWYG-Editor SummerNote Bug - [{ $oViewConf-&gtgetBaseDir() }] - https://www.proudcommerce.com/blog/summernote-wysiwyg-smarty-oxid-6

### suggest-dev list
* OXID SQL Logger ~ D3
* Module Generator ~ OXID eSales
* GraphQL Base ~ OXID eSales
* Smarty to TWIG Converter ~ OXID eSales
* 

## Installation

Run this command:

`composer require d3/recommended-modules-metapackage --update-no-dev`

## Show more recommended modules

Run this command:

`composer suggest d3/recommended-modules-metapackage`