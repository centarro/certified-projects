# Centarro Certified Projects
Drupal Commerce related projects maintained by Centarro to the same standards as Commerce Core.

These projects represent subsystems, features, or integrations that are not broadly used enough or appropriate for inclusion in Commerce Core. However, they are all developed according to Drupal / PHP best practices, compatible with both Commerce Core and other projects in this package, and documented at least via READMEs if not also via external documentation pages with screenshots or videos.

## Use in Commerce Kickstart

The primary purpose of this package is to collect in a single metapackage the various contributed projects we want to include in [Commerce Kickstart](https://www.drupal.org/project/commerce_kickstart). Commerce Kickstart is designed to be the fastest way to start building on Drupal Commerce. It provides an installation profile that can serve as a starting point for any new Drupal Commerce project along with a variety of feature modules for default configuration and an optional demo store.

We can guarantee the versions of the modules included in the package work well together and have sufficient documentation. We can also introduce new modules to existing Commerce Kickstart sites in the future by adding them to this package without making them dependencies of the profile itself. This means advanced developers who do not want the full suite of modules included in their codebases or who want to use different versions than we have certified can remove the `centarro/certified-projects` dependency after creating their projects and re-install just the modules they actually want.

## Included projects

### Subsystems

* [Commerce Shipping](https://www.drupal.org/project/commerce_shipping) - collect shipping fees and fulfill order shipments
* [Commerce License](https://www.drupal.org/project/commerce_license) - sell memberships, file downloads, and more

### Technology Partner integrations

* [Commerce PayPal](https://www.drupal.org/project/commerce_paypal)
* [Commerce Braintree](https://www.drupal.org/project/commerce_braintree)
* [Commerce Authorize.Net](https://www.drupal.org/project/commerce_authnet)
* [Commerce AvaTax](https://www.drupal.org/project/commerce_avatax)
* [Commerce Square](https://www.drupal.org/project/commerce_square)

### Feature modules

* [Commerce Email](https://www.drupal.org/project/commerce_email) - configure emails to be sent in reaction to order events
* [Commerce File](https://www.drupal.org/project/commerce_file) - sell file downloads through Commerce License
* [Commerce Pricelist](https://www.drupal.org/project/commerce_pricelist) - price subsets of your products by quantity, user, etc.
* [Commerce Product Limits](https://www.drupal.org/project/commerce_product_limits) - limit the purchaseable quantity of products
* [Commerce Product Tax](https://www.drupal.org/project/commerce_product_tax) - select a product's tax rate on its edit form
* [Commerce Store Domain](https://www.drupal.org/project/commerce_store_domain) - select the current store based on the domain

### Themes

* [Belgrade](https://www.drupal.org/project/belgrade) - Bootstrap based, mobile optimized store theme
* [Centarro Claro](https://github.com/centarro/centarro_claro) - customized version of Drupal core's Claro admin theme

## Roadmap

The following projects are on the short list for inclusion in future updates of this package.

* [Commerce Cart Estimate](https://www.drupal.org/project/commerce_cart_estimate)
* [Commerce CyberSource](https://www.drupal.org/project/commerce_cybersource)
* [Commerce Invoice](https://www.drupal.org/project/commerce_invoice)
* [Commerce Invoice Payment](https://www.drupal.org/project/commerce_invoice_payment)
* [Commerce Recurring](https://www.drupal.org/project/commerce_recurring)
* [Commerce Reports](https://www.drupal.org/project/commerce_reports)
* [Commerce Signifyd](https://www.drupal.org/project/commerce_signifyd)
* [Commerce Wishlist](https://www.drupal.org/project/commerce_wishlist)

We will tag a new patch version (e.g. 1.0.1, 1.0.2, etc.) when we increase the minimum version of a certified project. We will tag a minor version (e.g. 1.1.0, 1.2.0, etc.) when we add a new project to the metapackage. We will tag a new major release (e.g. 2.0.0) when projects are upgraded or added such that their compatibility with each other or Commerce Core versions are impacted.
