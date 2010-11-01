=== Mute Screamer ===
Contributors: ampt
Tags: phpids, intrusion detection, security, ids
Requires at least: 3.0
Tested up to: 3.1-alpha
Stable tag: 0.58

PHPIDS for Wordpress

== Description ==

Mute Screamer uses [PHPIDS](http://phpids.org/) to detect attacks on your Wordpress site and react in a way that you choose.

Requires PHP 5.2 or higher.

Features:

* View attack logs. Go to WP-Admin -> Dashboard -> Intrusions
* Send alert emails
* Configure PHPIDS exceptions, html and json fields
* Display a warning page
* Log users out of WP Admin
* Auto updates of default_filter.xml and Converter.php from phpids.org
* Auto update shows a diff of changes to be updated
* Removes all options and database tables when deleted via the Plugins admin page

== Installation ==

1. Copy the mute-screamer folder into /wp-content/plugins
2. Activate Mute Screamer via the plugins page in the Wordpress admin
3. Go to WP-Admin -> Settings -> Mute Screamer to configure

== Screenshots ==

1. Attack logs
2. Auto update diff

== Changelog ==

= 0.58 =

* Automatic updates of default_filter.xml and Converter.php from phpids.org
* Show a diff of changes during the auto update process
* Remove source column from intrusions list

= 0.32 =

* Fix where Mute Screamer would only allow bulk actions to run on Mute Screamer's intrusions page

= 0.31 =

* Requires PHP 5.2+
* Better IP detection
* Updated default exceptions
* Option to disable IDS in WP Admin
* Latest PHPIDS rules and converter
* Display a custom warning page to the user
* Bug: strip slashes of value before insertion into the database

= 0.22 =

* Fix missing fields in database logger

= 0.2 =

* Use wpdb instead of PDO for database logging
* Show new instrusions count badge in dashboard menu

= 0.17 =

* Fix search results for intrusions
* Fix empty exception fields

= 0.16 =

* Fix default exceptions list
* Merge existing options on activation

= 0.1 =

* Initial release.
