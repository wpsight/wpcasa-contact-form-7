=== WPCasa Contact Form 7 ===
Contributors: wpsight, kybernetikservices
Donate link: https://www.paypal.com/donate/?hosted_button_id=SYJNVSP2BKTQ4
Tags: real estate, wpcasa, contact form 7, cf 7, contact form, contact
Requires at least: 6.2
Tested up to: 6.7
Stable tag: 1.3.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add support for Contact Form 7 to attach property details to the contact email sent from WPCasa listing pages.

== Description ==

The WPCasa Contact Form 7 add-on is a bridge plugin for the Contact Form 7 form builder that can be used to display a contact form on single listing pages in WPCasa. The add-on makes sure that useful property information is attached to the emails sent through the form. It also comes with a starter form that includes all the necessary fields to make your life easier.

> Please notice that this plugin is an add-on for [WPCasa](https://wordpress.org/plugins/wpcasa/) and will NOT work without the core plugin.

WPCasa is a WordPress solution that provides an intuitive way to manage property listings and create first-class real estate websites.

* Website: [wpcasa.com](https://wpcasa.com)
* Demo: [demo.wpcasa.com](https://demo.wpcasa.com)
* Documentation: [docs.wpcasa.com](https://docs.wpcasa.com)

== Contributors ==
This is a list of contributors to WPCasa All Import.
Many thanks to all of them for contributing and making WPCasa All Import even better.

[Kybernetik Services](https://www.kybernetik-services.com/?utm_source=wordpress_org&utm_medium=plugin&utm_campaign=wpcasa&utm_content=readme)
[Joe Hana](https://wordpress.org/support/users/joehana/)
[codestylist](https://wordpress.org/support/users/codestylist/)

== Installation ==

= Automatic Installation =

Automatic installation is the easiest way to install WPCasa Contact Form 7. Log into your WordPress admin and go to _WP-Admin > Plugins > Add New_.

Then type "WPCasa Contact Form 7" in the search field and click _Install Now_ once you've found the plugin.

= Manual Installation =

If you prefer to install the plugin manually, you need to download it to your local computer and upload the unzipped plugin folder to the `/wp-content/plugins/` directory of your WordPress installation. Then activate the plugin on _WP-Admin > Plugins_.

== Frequently Asked Questions ==

= Will this plugin work without WPCasa or Contact Form 7? =

No, this is an add-on plugin for the WPCasa real estate framework in combination with the Contact Form 7 form builder and will not work without the corresponding core plugins.

= Where is the *.pot file for translating the plugin in any language? =

The translations are handled on WordPress.org. Please be part of the community and help to translate WPCasa Contact Form 7 on [GlotPress](https://translate.wordpress.org/projects/wp-plugins/wpcasa-contact-form-7/). Thank you!

== Screenshots ==

1. Contact Form 7 form on listing page
2. Contact Form 7 form editor
3. Contact Form 7 mail editor
4. Add-on tab on WPCasa settings page

== Changelog ==

= 1.3.0 =
* Add - Loading language files from [GlotPress](https://translate.wordpress.org/projects/wp-plugins/wpcasa-contact-form-7/).
* Add - Notice if WPCasa needs to be updated to get PHP 8 compatibility
* Fix - PHP8+ deprecated error about creation of dynamic property

= 1.2.1 =
* Fix - added version at wp_enqueue_style() to prevent cache problem
* Fix - some small improvements

= 1.2.0 =
* Fix - Compatibility issue with CF7 4.8
* Update - structure
* Add - listing agent name tag
* Add - compatibility with WPCasa 1.2 version
* ADD - recipient by default

= 1.1.0 =
* Fix - Compatibility issue with CF7 (Array > Object)

= 1.0.1 =
* Fix - Compatibility issue with CF7 (wpcf7_add_shortcode > wpcf7_add_form_tag())

= 1.0.0 =
* Initial release

== Upgrade Notice ==
= 1.3.0 =
We did some improvements for PHP 8 compatibility and translations are now handled on WordPress.org. Please be part of the community and help to translate WPCasa Contact Form 7 on [GlotPress](https://translate.wordpress.org/projects/wp-plugins/wpcasa-contact-form-7/). Thank you!

= 1.1.0 =
* Please find detailed instructions on our blog post: http://blog.wpcasa.com/plugin-update-wpcasa-contact-form-7-v1-1-0-now-available/