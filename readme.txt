=== Post Expirator ===
Contributors: axelseaa
Tags: expire, posts, pages
Requires at least: 2.5
Tested up to: 2.6
Stable tag: trunk

Allows you to add an expiration date (hourly) to posts which you can configure to either delete the post or change it to a draft.

== Description ==

The Post Expirator plugin allows the user to set expiration dates for both posts and pages.  There is a configuration option page in the plugins 
area that will allow you to seperataly control whether or not posts/pages are wither deleted or changed to draft status.

The plugin hooks into the wp cron processes and runs every hour.

The expiration date can be displayed within the actual post by using the [postexpirator] tag.  The format attribute will override the plugin 
default display format.  See the [PHP Date Function](http://us2.php.net/manual/en/function.date.php) for valid format options. 

== Wordpress MU ==

This plugin is compataibile with Wordpress MU 1.5+, however currently it will not work in the mu-plugins folder due to the plugin activation 
functions.

== Credits ==

Plugin is based on the orginial [Expiration Date](http://www.hostscope.com/wordpress-plugins/the-expirationdate-wordpress-plugin/) plugin by jrrl. 

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

**Version 1.2**

* Changed wording from "Expiration Date" to "Post Expirator" and moved the configuration options to the "Settings" tab.
* Added shortcode tag [postexpirator] to display the post expiration date within the post
* Added new setting for the default date display format
* Fixed bug where expiration date was removed when a post was auto saved

**Version 1.1**

* Expired posts retain expiration date

**Version 1.0**

* Initial Release

