=== Plugin Name ===
Contributors: lmwebdesign
Tags: attachments, custom post type, post attachments, zip files, downloads
Requires at least: 3.0.1
Tested up to: 3.9
Stable tag: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Takes the Custom Post Type > Post > Attachments logical structure and creates similar file tree structure.

== Description ==

This plugin reads the Custom Post Types (CPT) > Post > Attachment logical structure and creates a 
similar file tree structure with a few  clicks, example:

* CTP Name > Post Name > Attached File(s)
* CTP Directory > Post Name Directory > Attached File(s)

Directories can be created at the CPT or Post level, example:

* User creates directory at CTP level, "CTP > all Posts > Attachment(s)" tree is created. 
* User creates directory at Post level, "CTP > selected Post > Attachment(s)" tree is created

Once created they can be zipped at the CTP or Post level. Once zipped they can be directly downloaded.

== Installation ==

1. Download .zip file.
2. Extract to `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= It's not creating an entire file tree for my Custom Post Type and/or Post =

By default the script in charge of making the file tree structure has a run time limit of 120secs. 
If you have a Custom Post Type with a large number of Posts and/or many Attachments edit the lmwd-file-handler.php file
and increase `set_time_limit(120);`. 


== Screenshots ==

1. Drop down tree display

== Changelog ==

= 1.0 =
* First Version

* FUTURE UPDATES
* Work with regular Posts
* Add Category filing

== Upgrade Notice ==

None


== Arbitrary section ==




