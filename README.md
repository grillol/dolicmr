# DOLICMR (http://www.dolifarm.com)

## FEATURES

<!--
![Screenshot dolitrace](img/screenshot_dolitrace.png?raw=true "DoliTrace"){imgmd}
-->
This package is a module of [Dolibarr](http://www.dolibarr.org) [GitHub/Dolibarr](https://github.com/Dolibarr/dolibarr/)

You can freely use, study, modify or distribute it according to its licence.

The module is part of the doliFARM suite. [Dolifarm.com](https://www.dolifarm.com) - [GitHub/grillol](https://github.com/grillol/dolifarm).

doliCMR allows the [CMR waybill](https://en.wikipedia.org/wiki/CMR_Convention) to be generated from the shipment information. 

NB. This module is still in an embryonic stage.  
It was developed for a specific case [Mandala OG](http://www.mandalaorganicgrowers.com) and there are several aspects to be improved. Not least, the e-CMR project https://uptr.be/fr/informations/e-cmr-lettre-de-voiture-electronique/ needs to be evaluated.
It works parsing product description with the following format:  

        Abricots Tsunami | Apricots Tsunami BIO
        108 X 6kg = 648kg (694.5kg BRUT)
        Lotto N. 4390869
        ORIGINE ITALIA

## REQUIREMENTS
This module requires a Dolibarr platform installation. It has been tested for the version > 13

## TRANSLATION

Translations can be completed manually by editing files into directories *langs*.


## INSTALLATION

It follows the standard installation for the Dolibarr module. For more information: [official Dolibarr documentation](https://wiki.dolibarr.org/).


## WHAT DOLICMR CAN'T DO YET
- Elaborate different CMR starting from the same shipment
- Provide API for external access to the CMR

## CONTRIBUTING

## LICENSE

### Main code

DoliCMR is released under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or (at your option) any later version (GPL-3+).

See the COPYING file for a full copy of the license.

Other licenses apply for some included dependencies. See COPYRIGHT for a full list.

### Documentation

All texts and readmes are licensed under GFDL.
