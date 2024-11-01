=== Wolfiz Stripe Meta Data Settings ===
Contributors: wolfiz
Donate link: https://wolfiz.com
Tags: stripe, woocommerce
Requires at least: 4.6
Tested up to: 4.9
Stable tag: 1.0
Requires PHP: 5.2.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Wolfiz Stripe Meta Data Settings plugin adds a new tab in woocommerce settings so woocomerce product name, order number and quantity can be displayed inside stripe transaction meta data area.

== Description ==

Wolfiz Stripe Meta Data Settings plugin adds a new tab in woocommerce settings. It gives three settings of checkboxes.

1) Show product name.
2) Show order number.
3) Show quantity.

Enable these settings if you want to add product name, order number or quantity in meta data area of stripe transaction inside stripe payment menu.
 
Enabling Show product name setting will show product name in the metadata of stripe payment menu.

Enabling Show order number setting will show woocommerce order number in the metadata of stripe payment menu.

Enabling Show quantity setting will show woocommerce item quantity in the metadata of stripe payment menu.


== Installation ==

1. Upload the plugin files to the '/wp-content/plugins/', or install the plugin through the WordPress plugins screen directly.

2. Activate the plugin through the 'Plugins' screen in WordPress.

3. Use the woocommerce > Settings > Stripe Meta Data to configure the stripe metadata settings.

== Screenshots ==

1. The woocommerce stripe metadata settings tab screen. It show three settings for stripe based payment in woocommerce.

2. Displaying product name, order number and quantity inside stripe transaction.

== Contributors & Developers ==

"Wolfiz Stripe Meta Data Settings" is open source software. 
Please visit http://www.wolfiz.com for more information and details of the developers.

== FAQ == 

Manual Installation

Navigate to the 'Add New' in the plugins dashboard.

Navigate to the 'Upload' area.

Select wolfiz_stripe_metadata_settings.zip from your computer.

Click 'Install Now'.

Activate the plugin in the Plugin dashboard.


Using FTP

Download wolfiz_stripe_metadata_settings.zip.

Extract the wolfiz_stripe_metadata_settings.zip directory to your computer.

Upload the wolfiz_stripe_metadata_settings.zip directory to the /wp-content/plugins/ directory.

Activate the plugin in the Plugin dashboard.


Q) Is there any effect on order information of woocommerce by using this plugin?.

A) No, this plugin only modify metadata of transaction forwarded to stripe.

Q) Will this plugin work with any other Form/plugin where stripe is enabled as payment gateway?.

A) No, this plugin will only work with woocommerce.

