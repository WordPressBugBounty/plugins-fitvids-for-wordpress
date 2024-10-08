=== FitVids for WordPress ===
Contributors: kevindees
Tags: videos, fitvids, responsive
Requires at least: 6.5
Requires PHP: 8.2
Tested up to: 6.6
Stable Tag: 4.0.1

This plugin makes videos responsive using the FitVids jQuery plugin on WordPress.

== Description ==

This plugin makes videos responsive using the FitVids jQuery plugin on WordPress.

The options page is located on the dashboard menu under Appearance as "FitVids". FitVids always works with YouTube, Vimeo, Blip.tv, Viddler, and Kickstarter. Use simple jQuery selectors, on the admin page, like `body`, `article, aside` and `.post` to customize what videos become responsive.

You can set custom selectors to include videos from any provider. You are not limited to the list that comes with FitVids by default.

== Installation ==

Upload the fitvids-for-wordpress plugin to your blog, Activate it!

== Screenshots ==

1. If you need help understanding how FitVids works click the help tab.

== Changelog ==

= 4.0.1 =

* Fix version bug.

= 4.0.0 =

* Update plugin to require PHP 8.2.
* Update jQuery to version 3.7.1 from 3.4.1.

= 3.0.13 =

* Update plugin version.

= 3.0.12 =

* Add WP 6.1
* Add youtu.be support.

= 3.0.11 =

* Add WP 6.0

= 3.0.10 =

* Add WP 5.9

= 3.0.9 =

* Add WP 5.7 & 5.8

= 3.0.8 =
* Add WP 5.6

= 3.0.7 =
* Add WP 5.5

= 3.0.6 =
* Update plugin version
* Update author URL

= 3.0.5 =
* Update version of jQuery to 3.4.1

= 3.0.4 =
* Add Facebook by default
* Update version
* Add author name

= 3.0.3 =
* Fix activation bug

= 3.0.3 =
* Add help tab
* Make default selector visible

= 3.0.1 =
* Update FitVids Version
* New admin settings page
* Add FitVids ignore
* Better security
* Update selector input configuration. You might need to update your custom settings.

= 2.1 =

* Add support for custom video players
* Update FitVids (bug fixes on github)
* Fix load order with add_action('wp_print_footer_scripts', array($this, 'add_fitthem'))
* Added better help text

= 2.0.1 =

* Fix define('DISALLOW_FILE_EDIT',true) bug by changing edit_themes to switch_themes

= 2.0 =

* Added Security Fix
* Changed capabilities to edit_themes instead of administrator
* Added New Version of FitVids
* Added jQuery 1.7.2 from Google CDN
* Added better readme
* Redesigned settings page

= 1.0.1 =

* Fixed readme description
* Changed saving feature in php
* Added uninstall.php to remove options

= 1.0 =

* Make videos responsive using FitVids.js