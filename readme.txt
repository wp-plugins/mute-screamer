=== Mute Screamer ===
Contributors: ampt
Tags: phpids, intrusion detection, security
Requires at least: 3.0
Tested up to: 3.0
Stable tag: 0.15

PHPIDS for Wordpress

== Description ==

Mute Screamer uses [PHPIDS](http://phpids.org/) to detect attacks on your Wordpress site and reacts in a way that you choose.
Currently there is support for sending an alert email when an attack is detected.

Requires PHP 5.1.6 or greater.


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

= 0.15 =

* Fix default exceptions list
* Merge existing options on activation

= 0.1 =

* Initial release.
