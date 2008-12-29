=== Post Expirator ===
Contributors: axelseaa
Tags: expire, posts, pages
Requires at least: 2.5
Tested up to: 2.6
Stable tag: trunk

Allows you to add an expiration date (hourly) to posts which you can configure to either delete the post or change it to a draft.

== Description ==

The Post Expirator plugin allows the user to set expiration dates for both posts and pages.  There is a configuration option 
page in the plugins area that will allow you to separately control whether or not posts/pages are either deleted or changed to 
draft status.

The plugin hooks into the wp cron processes and runs every hour.

== Wordpress MU ==

This plugin is compataibile with Wordpress MU 1.5+, however currently it will not work in the mu-plugins folder due to the plugin activation 
functions.

== Credits ==

Plugin concept is based on the orginial [Expiration Date](http://www.hostscope.com/wordpress-plugins/the-expirationdate-wordpress-plugin/) plugin by jrrl. 

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

**Version 1.1**

* Expired posts retain expiration date

**Version 1.0**

* Initial Release

