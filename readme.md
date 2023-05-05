WooCommerce - Flickity Gallery (WordPress Plugin)
==

_Turn your WooCommerce featured image and gallery photos into an interactive image carousel using Flickity._

    Contributors: komodo016
    Donate link: https://www.paypal.com/paypalme/komodo016
    Tags: woocommerce, flickity, gallery, carousel, product
    Requires at least: 4.1
    Tested up to: 4.5.3
    Stable tag: (none)
    License: GPLv3
    License URI: http://www.gnu.org/licenses/gpl-3.0.txt

## Description ##

This plugin replaces the standard WooCommerce featured image and product thumbnails with an image slider / carousel powered by [Metafizzy's Flickity](http://flickity.metafizzy.co/) library.

There are no configurable options, simply activate the plugin and you are done. The slider uses WooCommerce's product photo image sizes or else falls back to WordPress defaults.

## Installation ##

1. Upload the plugin files to `/wp-content/plugins/wc-flickity-gallery/`, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Visit one of your products to see the new slider in action.

## Frequently Asked Questions ##

**What about products with just one photo, or no photos?**

If only one image is detected, it is displayed as a standard featured image, with no slider behavior.

**What if there aren't any photos for a product?**

It will use a placeholder similar to the default WooCommerce behavior.

**Can this be used outside of WooCommerce, such as for a gallery shortcode?**

No, the Flickity assets are only loaded on single product pages. If you want to use a gallery for other purposes, you should look for a different plugin.

## Screenshots ##

![The Flickity slider in action for a ceiling fan product](screenshot-1.jpg)
![Another product with fewer thumbnails](screenshot-2.jpg)

## Changelog ##

#### 1.0.1
* Enabled swiping the primary gallery. Continues to open a lightbox, only if you did not swipe first.

#### 1.0.0
* First release

## Upgrade Notice ##

Upgrading from 1.0.0 to 1.0.1 introduces a new version of Flickity. It should not have any adverse affects on your website, unless you are using flickity elsewhere. If you are, then you should make sure those flickity galleries continue to work as expected.
