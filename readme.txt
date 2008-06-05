=== Featurific For Wordpress ===
Contributors: rinogo
Donate link: http://featurific.com/
Tags: slideshow, slide, show, gallery, flash, xml, dynamic, conversion, funnel, Post, posts, sidebar, images, links, photo, photos, statistics, stats, swf, plugin, admin
Requires at least: 2.3
Tested up to: 2.5
Stable tag: trunk

An effortless but powerful interface to Featurific Free, the featured story slideshow.  (Similar to the 'featured'
widget on time.com, msn.com, walmart.com, etc.)



== Description ==

An effortless interface to Featurific Free, the featured story slideshow.

Unlike traditional slideshows, Featurific imitates the behavior seen on the home pages of sites like time.com and msn.com,
displaying summaries of featured articles on the site.  The idea is to increase conversion and user satisfaction by
funneling your readers to your strongest, most engaging content.  If you believe that big budget companies like Time, MSN,
and Walmart might be on to something, then give this plugin a shot.

Installation is automatic and easy, while advanced users can customize every element of the Flash slideshow presentation.

Selected feature list:
* No configuration required (although you can tweak nearly any aspect of the plugin if you so desire)
* User-customizable templates
* Integrates with the Wordpress.com Stats Plugin to select most popular posts
* Customizable options include number of posts to display, post selection type, screen duration, auto-excerpt length, etc.



== Installation ==

Standard Wordpress installation (no fancy config steps required):

1. Extract all files from FeaturificForWordpress.zip.
1. Upload the entire `featurific` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. You're done! :)

For basic configuration, visit the 'Settings' menu and access the submenu named 'Featurific'.



== Demo Sites ==
Once you get Featurific for Wordpress installed, please email me and I'll add you to this list of demo sites.
(Hey, free traffic! :) ) (rich at [please don't spam me] byu period net)

[Sox & Dawgs](http://soxanddawgs.com/) |
[Endorkins](http://endorkins.com/) |
[Passion for Poetry](http://p4poetry.com/) |
[C'mon Yu Irons!](http://cmonyuirons.com) |
[Esperto Seo](http://www.espertoseo.it)




== Changelog ==
**1.2 (6/4/08)**
Changelog added.  Unicode Support (UTF-8 encoding) added to FeaturificFree.swf.



== Frequently Asked Questions ==

= I can't get the plugin to install.  What's up? =
I'm sorry if the plugin is causing you problems.  It has only recently been released (consider yourself an early
adopter! :) ), so I still need to work through the bugs that weren't manifest in my development environment.  Please
email me (rich at [please don't spam me] byu period net) and I'll be happy to help you work through the bugs.

= Where can I find more templates? =
[The Featurific website](http://featurific.com/ffw) ([http://featurific.com/ffw](http://featurific.com/ffw)).  No
extra templates have been released yet - please let me know if you'd like your template to be the first featured
template!


= What are the system requirements for using Featurific? =
Featurific has been successfully tested with Wordpress 2.3 to 2.5.1 on PHP4 and PHP5.  If you have problems on these
(or other) configurations, feel free to email me.  (rich at [please don't spam me] byu period net)


= How do I move Featurific to another location on my page? =

Many Featurific templates look better in a sidebar than in the main content area.  To move Featurific to the side bar or
any other location, just edit your theme.  Featurific for Wordpress automatically inserts itself into your index.php or
home.php theme file (whichever it detects is present).  Open up the file and look for the following code:

`//Code automatically inserted by Featurific for Wordpress plugin
if(is_home())                             //If we're generating the home page (remove this line to make Featurific appear on all pages)...
 if(function_exists('insert_featurific')) //If the Featurific plugin is activated...
  insert_featurific();                    //Insert the HTML code to embed Featurific`

Move this code to wherever you'd like Featurific to appear (in any of your theme files).


= How do I make Featurific appear on pages other than the main page? =

**Theme file**
If you've got a *theme file that corresponds to the pages on which you want Featurific to appear*, just follow the
instructions under the FAQ entry, "How do I move Featurific to another location on my page?".  Move the Featurific code to
the desired location in the appropriate theme file.

**All pages**
If you want Featurific to appear on *all* pages and not just on the home page, find the following code in your theme's
index.php or home.php file:

`//Code automatically inserted by Featurific for Wordpress plugin
if(is_home())                             //If we're generating the home page (remove this line to make Featurific appear on all pages)...
 if(function_exists('insert_featurific')) //If the Featurific plugin is activated...
  insert_featurific();                    //Insert the HTML code to embed Featurific`

Comment out the line that begins with `if(is_home())` by inserting '//' at the beginning of the line as follows:

`//Code automatically inserted by Featurific for Wordpress plugin
 //if(is_home())                             //If we're generating the home page (remove this line to make Featurific appear on all pages)...
 if(function_exists('insert_featurific')) //If the Featurific plugin is activated...
  insert_featurific();                    //Insert the HTML code to embed Featurific`

**Specific pages**
If you want Featurific to appear on specific pages, you could try using `$_SERVER['REQUEST_URI'])` and either an if
statement or the `preg()`/`pregi()` functions (regular expressions).


= I hate the logo that appears in the corner all the time.  How can I get rid of it? =
To get rid of the "Powered by Featurific" logo, you're going to have to splurge for the commercial version of Featurific.
[Visit the Featurific website](http://featurific.com) for details ([http://featurific.com](http://featurific.com)).


= I can't get this thing to work!  What's wrong? =
Drop me an email and I'll try to help you out.  (rich at [please don't spam me] byu period net)



== Screenshots ==

1. The options page for the Featurific for Wordpress plugin.
2. An example of the plugin in action.
3. An example of the plugin in action.
4. An example of the plugin in action.
5. An example of the plugin in action.
6. An example of the plugin in action.
7. An example of the plugin in action.
