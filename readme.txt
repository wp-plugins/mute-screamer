=== Mute Screamer ===
Contributors: ampt
Tags: phpids, intrusion detection, security, ids
Requires at least: 3.0
Tested up to: 3.1-alpha
Stable tag: trunk

PHPIDS for Wordpress

== Description ==

Mute Screamer uses [PHPIDS](http://phpids.org/) to detect attacks on your Wordpress site and reacts in a way that you choose.
Currently there is support for sending an alert email when an attack is detected.

Requires PHP 5.1.6 or higher.


Features:

* View attack logs. Go to WP-Admin -> Dashboard -> Intrusions
* Send alert emails
* Configure PHPIDS exceptions, html and json fields
* Removes all options and database tables when deleted via the Plugins admin page

== Installation ==

1. Copy the mute-screamer folder into /wp-content/plugins
2. Activate Mute Screamer via the plugins page in the Wordpress admin
3. Go to WP-Admin -> Settings -> Mute Screamer to configure

== Screenshots ==

1. Attack logs

== Changelog ==

= 0.21 =

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
