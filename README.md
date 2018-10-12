# Odoo Product Configurator
Odoo modules enabling dynamic product configuration

The product configurator modules suite prevents automatic generation of variants in Odoo and provides on-demand generation through friendly user interfaces.

# Test our latest version on runbot

You can always view our latest unreleased changes on our runbot by [clicking here](http://runbot.pledra.com)


# Contribute & help us improve

The Odoo product configurator module suite is the result of a community effort. Support from users was key to start this project and it is key for keeping it alive and opensource.

Consider donating or contacting us for other funding options (invoice / pre-release etc) in order support and maintain the modules opensource. (contact@pledra.com)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RZHQEDQW7Q8JS)

# Upgrades & Roadmap

* Product configurator is now an app and has a root main menu.

![Menu-Root](https://i.imgur.com/yvu0nDA.png)
 
* Wizard is now integrated with product_configurator module (product_configurator_wizard removed).
* Wizard is now a generic extensible object ( _inherit / _inherits ) which can create derivatives (sale, mrp, stock etc) configurators or adapt the base one.

![New-Wizard](https://i.imgur.com/oS0XfBo.png)
* New configurator modules:
    * product_configurator_purchase
    * product_configurator_stock
    * product_configurator_subconfig
    * product_configurator_sale_mrp
* Specify default values for configurable templates

![Default Values](https://i.imgur.com/wsZvoAJ.png)

* Configurations can now be made directly from the configurable template.
* Sessions now store the configuration step you were in the last incomplete configuration (useful for long configuration processes).
* MRP Wizard can offer subconfigurable products (nested configurable products & nested configuration sessions).

![Subconfiguration](https://i.imgur.com/NCJnOY9.png)
* Quantities can now be specified inside the mrp configuration wizard.
* Multiple session/configuration related methods moved from product.template to product.config.session (eases a lot of convoluted designs to obtain configuration data since the configuration session is the heart of any configuration option not the product.template).
* Dynamic field value are now stored as class property (less overhead for obtaining the values).
* Price computation can uses the standard attribute value extra field for non-mrp scenarios
* Loads of bug fixes from previous versions.


# Credits

### Investors

* initOS
* Firma Casper Francke
* WilldooIT
* Camptocamp
* Madsack Media Store
* OpenIndustry.it
* Asphalt Zipper
* Access Windows and Doors Inc
* BIG Consulting GmbH
* Ursainfosystems
* IT IS AG

Maintainer
----------

[![Pledra Logo](https://www.pledra.com/logo.png)](https://www.pledra.com/)
