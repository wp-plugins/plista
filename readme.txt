=== plista ===
Tags: advertising, recommendations, plista, similar items, ads, related articles
Donate link: http://www.plista.com
Contributors: plista.com
Text Domain: plista
Requires at least: 2.5.0
Tested up to: 3.3.1
Stable tag: 1.3.6

The plista Widget adds plista RecommendationAds to your Wordpress blog posts.

== Description ==

= Advantages =

- First advertising format with visitors Value
- Increase traffic and sales
- Increase of user Session Duration
- Free and easy Registration
- No contract term

The new preference based plista advertising format offers an innovative solution for publishers to promote their products and websites with much better efficiency.
You can showcase user-specific content in a relevant context with our advertising format 
The key technology of plista filters content across your sites and determines its relevance.
Visitors to your website, only get recommendations based on individual preferences which allow precise targeting for publishers.

= Translations =

* Spanish (es_ES) - Ramon Navarro
* English (en_GB) - plista

== Premises ==

PHP5 is required for the use of this Plugin

== Installation == 

1. Register on http://www.plista.com/publisher_registrations to be able to use the Widget.
2. Wait till your Domain has been reviewed and unlocked by plista. The Widget is not usable without approval.
3. Login to your Administration Page.
4. In the Navigation menu on the left, click Plugin and then the submenu install.
5. Search for "plista", install and activate the plugin from the Author "wordpress@plista.com".
6. Go to the plista Dashboard (https://www.plista.com/publishers/dashboard). You can locate the "Data view" table right under the "visual view" table. 
7. Search for the Widget you wish to use and click on the icon in the "integration" column. 
8. A pop-up window with the "public key" and the "widget name" should show. Both values are needed to activate your plugins.
9. Go back to your Wordpress Admin and click "plista" under the navigation item settings. Now enter the widget name and public key under the basic settings and save.
10. Further modifications for the widget can be done here if wished. / If you want you can also make additional settings in your widget here.
11. Please insert the following in your theme file(e.g. single.php), in case you checked the box for Auto insert.
'<?php if (class_exists('plista')) { echo plista::plista_integration ($content); } ?>'
12. The plista plugin is now active and can be used.

== Frequently Asked Questions ==
= Where do I get the "name of the widget" and the "public key" required for the settings of the plugin? =
The "name of the widget" and the "public key" are available after registration on https://www.plista.com/publisher_registrations
These details are also available on the Publisher Dashboard in the table "Data view": https://www.plista.com/publishers/dashboard
Click the icon in the "integration" column and you will get all the necessary information displayed.

= Why are no Ads displaying on my Website? =
Ads are only unlocked after a more detailed check of your Website from plista. 
This check usually happens within a few working days. In any case, you will be notified. 

= Why is the Message "plista has been successfully installed" displayed? =
This Message will disappear after we have received about 10 items from your site.

For more questions please visit our FAQ's: https://www.plista.com/de/publishers/info/faq

== Upgrade Notice ==

Please upgrade to Version 1.4.0

== Screenshots ==

1. plista Adminpage
2. An Example of our plista Widgets

== Changelog ==

1.0 @ 09-22-2011
    * first official release

1.1 @ 09-23-2011
    * major relase

1.2 @ 10-05-2011
    * better handling for img indexing
    * english translation v1

1.2.1 @ 10-31-2011
    * fixes picture related bugs

1.3.0 @ 12-07-2011
    * use wp_head to set custom css
    * improved styles for admin page
    * possibility to change widget style for mobile design (wp touch required)
    * possibility to set a default image

1.3.1 @ 12-08-2011
    * plista_integration function is no global available

1.3.2 @ 01-04-2012
    * fix css bugs
    * added new possibilities to style the widget
    * added possibility to exclude categories for pictureAds
    * tested functionality width WordPress 3.3.1

1.3.3 @ 01-27-2012
    * change order of image indexing
    * added Spanish translations
    * jslint javascript used for admin page
    * added notice to contact plista before activating pictureAds
    * added possibility to exclude tags

1.3.4 @ 01-30-2012
    * fix warning if no tags are available

1.3.5 @ 02-07-2012
    * don't look for youtube image if no youtube video is present

1.3.6 @ 24-03-2014
    * remove PHP version in comment tag

1.4.0 @ 16-04-2015
    * use the async version of plista
    * add option to exclude post types
    * index created_at and category
    * remove picture ads
    * don't index pages if user is logged in and previews site