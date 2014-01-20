=== Bootstrap Shortcodes for WordPress ===
Contributors: filipstefansson, nodley, FoolsRun
Tags: bootstrap, shortcode, shortcodes, responsive, grid
Requires at least: 3.8
Tested up to: 3.8
Stable tag: 3.0.3.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Implements Bootstrap 3 styles and components in WordPress through shortcodes.

== Description ==

###Just The Shortcodes, Please
Plenty of great WordPress plugins focus on providing or including the Bootstrap library into your site. **Bootstrap Shortcodes for WordPress** assumes you're working with a theme that already includes Bootstrap 3 and focuses on giving you a great set of shortcodes to use it with.

This plugin creates a simple, out of the way button just above the WordPress TinyMCE editor (next to the "Add Media" button) which pops up the plugin's documentation and shortcode examples for reference and handy "Insert Example" links to send the example shortcodes straight to the editor. There are no additional TinyMCE buttons to clutter up your screen, just great, easy to use shortcodes!

If you like this plugin, check out our companion plugin for Font Awesome, [Font Awesome Shortcodes](http://www.wordpress.org/plugins/font-awesome-shortcodes/)

###Supported Shortcodes
####CSS
* Grid
* Lead body copy
* Emphasis classes
* Code
* Tables
* Buttons
* Images
* Responsive utilities
####Components
* Button Groups
* Button Dropdowns
* Navs
* Breadcrumbs
* Labels
* Badges
* Jumbotron
* Page Header
* Thumbnails
* Alerts
* Progress Bars
* Media Objects
* List Groups
* Panels
* Wells
####JavaScript
* Tabs
* Tooltip
* Popover
* Collapse (Accordion)
* Modal

== Installation ==
1. Download and unzip this plugin
1. Upload the "bootstrap-3-shortcodes" folder to your site's `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Create or edit a page or post and click the "B" button that appears above the editor to see the plugin's documentation!

== Frequently Asked Questions ==

= Does this plugin include Bootstrap 3? =

No, we assume you are already working with a WordPress theme that includes the Bootstrap libraries.

== Changelog ==

= 3.0.3.2 =
* Fix help tab popup on edit pages

= 3.0.3.1 =
* Change help-tab to inline rather than iframe in to meet WordPress.org submission requirements
* Add support for images (http://getbootstrap.com/css/#images)
* Add support for progress bars (http://getbootstrap.com/components/#progress)
* Add support for page header (http://getbootstrap.com/components/#page-header
* Improve list groups, add support for linked items and custom content (http://getbootstrap.com/components/#list-group)
* Add support for button dropdowns (http://getbootstrap.com/components/#btn-dropdowns)
* Add support for breadcrumbs (http://getbootstrap.com/components/#breadcrumbs)
* Add support for button-toolbar in button groups (http://getbootstrap.com/components/#btn-groups-toolbar)
* Add support for navs (http://getbootstrap.com/components/#nav)
* Remove "strong" parameter from alerts --this should be handled in the wrapped content
* Allow arbitrary classes in columns

= 3.0.3 =
* Initial WordPress.org release