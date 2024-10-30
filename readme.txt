=== Birch Layered Nav ===
Contributors: danyn
Tags: woocommerce, layered nav, product categories, variable products, e-commerce, ecommerce, sales, sell, store
Requires at least: 4.4
Tested up to: 4.7.4
Stable tag: 1.0
WC requires at least: 3.0.0
WC tested up to: 3.0.4

License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin extends WooCommerce Layered Nav Widget. As such the latest stable release of WooCommerce is a dependancy. It Still Allows the user to refine products based on attributes in product category pages.  It adds the ability to show a layered nav only on specific product categories.  This is useful because it allows the Layered Nav which is essentially a product filter to reflect only the attributes of a given product category. It also adds the information from the layered nav onto the links to variable products so that choices made by a shopper are still intact on the Select Options page of variable products. This plugin will not run unless the WooCommerce plugin is active. 

== Description ==
This plugin extends WooCommerce Layered Nav Widget in three important ways
*It shows a given layered nav only on the product categories you declare 
*It makes the entire layered nav button area clickable including the checkbox
*It adds information from the Layered Nav Widget  onto the links of variable products in order to save the user a few click once they land on the variable product page.


== Installation ==

Birch Layered Nav extends WooCommerce Layered Nav as such WooCommerce must be installed and its widgets class must be present.  This is default for the active WooCommerce Plugin.


1. Upload the plugin files to the `/wp-content/plugins/birch-layered-nav` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Appearance Widgets Screen to configure the Layered Nav
1. Familiarize yourself with the operation of the WooCommerce Layered Nav this widget is used exactly the same way and adds only one additional field which is a comma separated list of the slugs of WooCommerce Product Categories you want the given filter to show on. Make sure the comma separated list contains no spaces as such (shirts,hats,socks) not (shirts, hats, socks)
1.These slugs of WooCommerce Product Categories are viewable the following admin screen: Products->Categories


== Frequently Asked Questions ==

= Why is the Birch Layered Nav not showing? =

You must enter the slug of the Prodcut Categories you want the Birch Layered Nav to be displayed on.  Also those products must have attributes that match the attributes the Layered Nav is filtering on.  This also works well for Variable Products.



== Screenshots ==

1. Select A Birch Layered Nav

2. Provide a Space Separated List of Product Categories, a Title, and the Atribute to filter on

== Changelog ==

= 1.0 =
* initial release





