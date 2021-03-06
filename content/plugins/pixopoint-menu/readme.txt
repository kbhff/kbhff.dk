=== PixoPoint Menu Plugin ===
Contributors: ryanhellyer
Donate link: http://pixopoint.com/donate/
Tags: menu, navigation, dropdown, superfish, suckerfish, jquery
Requires at least: 3.4
Stable tag: 0.6.30

This plugin has been retired and is no longer under active development.

== Description ==

This plugin has been retired. It serves little purpose any longer and has many problems which I do not have time to fix. A better solution is to use the menu system built into WordPress core. If you desperately require similar functionality to this plugin, try my other plugin the "<a href="http://pixopoint.com/products/multi-level-navigation/">Multi-level Navigation plugin</a>" which is almost identical, but will be around for a long time to come.

Adds an SEO friendly, accessible regular or dropdown menu to your WordPress blog. Visit the <a href="http://pixopoint.com/products/pixopoint-menu/">PixoPoint Menu Plugin page</a> for more information about the plugin.

= Features =

* Control content will be displayed in the menu<br />
* Easy to use interface for modifying the design<br />
* Animation drodpown menus<br />
* Up to two menus<br />
* Plus much more<br />

= Changing the look of your menu =

To control the design of your menu, check out the <a href="http://pixopoint.com/suckerfish_css/">PixoPoint Menu CSS generator</a>.

Special thanks to <a href="http://transientmonkey.com/">Greg Yingling (aka malcalevak)</a> who was a massive help with optomising the code for this plugin.

== Installation ==

After you've downloaded and extracted the files:

Visit the <a href="http://pixopoint.com/products/pixopoint-menu/">PixoPoint Menu Plugin page</a> for more information about the plugin.

1.  Upload the complete `pixopoint-menu` folder to the `/wp-content/plugins/` directory OR install it via the WordPress plugin repository browser<br />
2.  Activate the plugin through the 'Plugins' menu in WordPress<br />
3. Either: Add `<?php if ( function_exists( 'pixopoint_menu' ) ) {pixopoint_menu();} ?>` to your theme wherever you want the menu to appear (usually your header.php file).<br />
4.  Visit the "PixoPoint Menu" page in your WordPress settings menu<br />
5.  Control how the menu behaves via the plethora of different options
6.  Click the 'Load editor' button to modify the design via the easy to use editing panel<br />

= Easy installation =

Some themes such as <a href="http://themehybrid.com/">Hybrid</a>, <a href="http://thematic.com/">Thematic</a> and Thesis allow the plugin to appear in the theme by choosing the 'Auto theme support' under 'Settings' in the plugins admin page. This option will also work in many other themes, it's worth trying  at least but we can't guarantee it will work (the theme requires <?php wp_page_menu(); ?> for it work).

If your theme doesn't already support the PixoPoint menu plugin then read on for simple instructions on how to integrate it into other themes ... it isn't very hard

= Premium Support =

I no longer provide paid support for menu issues sorry.

= Free support =

I no longer provide free support for menu issues sorry.

== Frequently Asked Questions ==

= Why can't the plugin do X, Y or Z? =

It probably can, I just haven't supplied instructions on how to do it. If you have any requests, then please leave them in the <a href="http://pixopoint.com/forum/index.php?board=4.0">PixoPoint menu support board</a>. We often update the plugin with new functionality and we're far more likely to include the functionality you want if we know there is a demand for it already.

= Why should I use this plugin? =

If you want to create a dazzling, custom designed menu without writing and bug fixing endless lines of code.

If you are having trouble making your posts easily accessible to your users without them having to rifle endlessly through pages of posts.

If you have been using a menu which requires javascript to work, then this plugin will allow more of your visitors to access your site.

If you want to have an easy way to style your dropdown menu. This plugin allows you to control exactly how your menu appears on your site via an easy to use interface. It is also 100% compatible with the code generated on the <a href="http://pixopoint.com/suckerfish_css/">Suckerfish Dropdown CSS Generator page</a>.

= Does it work for WordPress version x.x.x? =

The plugin is designed to work with the latest version of WordPress only. We do not provide backwards support.

== Screenshots ==

Visit the <a href="http://pixopoint.com/products/pixopoint-menu/">PixoPoint Menu Plugin page</a> for more information about the plugin.

1. The administration page for the <a href="http://pixopoint.com/pixopoint-menu/">PixoPoint Menu plugin</a>, where you can modify what appears in your menu by drag and dropping the various menu items. By clicking the tabs at the top of the page you can access sections for modifying various features of the plugin. The 'Load Editor' button loads the editing panel as shown below.
2. The 'Settings tab' from the administration page for the <a href="http://pixopoint.com/pixopoint-menu/">PixoPoint Menu plugin</a>, where you can modify a variety of different features in the plugin.

== Changelog ==

= 0.6.30 =
* Critical functionality fix to allow plugin to keep working
= 0.6.29 =
* Retiring of plugin
* Multiple security fixes.
* Possibly the last updated version
* Removed crazy amounts of dead code
= 0.6.28 =
* Multiple security fixes.
= 0.6.27 =
* Another attempt to fix the SVN repo.
= 0.6.26 =
* Another attempt to fix the SVN repo.
= 0.6.25 =
* Bug fix. SVN did not update all the plugin files last time :(
= 0.6.24 =
* Error fixed in documentation (required version was incorrect)
= 0.6.23 =
* Massive upgrade to documentation (there was lots of incorrect information in our plugin pages)
= 0.6.22 =
* Performance enhancement
* Slightly fasterer menu loads
= 0.6.21 =
* Security hardening release
	- Corrected issue which affected non-trusted admins (typically multisite admins)
	- Disabled javascript in custom menu items
	- Performs security checks on CSS too
= 0.6.20 =
* Auto-upgrade failed on previous update. Now fixed.
= 0.6.19 =
* Fixed bug which caused a clash with the MyPageOrder plugin
= 0.6.18 =
* Invalid code caused by "Recent Posts" fixed
= 0.6.17 =
* Invalid code caused by "Categories with posts" fixed
= 0.6.16 =
* Removed incorrect } in installation instructions for wp_page_menu()
* Replaced is_home with is_front_page in core.php (allows for display current_page_item correctly when using a static home page)
= 0.6.13 to 0.6.15 =
* Security update
	- Temporarily removed editing panel to prevent potential hack
	- Fixed bug which may have allowed the CSS in your menu to be modified by hackers
	- White listed settings
= 0.6.12 =
* New stable version
* Readme.txt file updated correctly
= 0.6.11 Beta =
* Multiple years bug in Years and Months option corrected
= 0.6.10 Beta =
* HTML validation bug in Years and Months option corrected
= 0.6.9 Beta =
* Added Years and Months support to Archives option on request of a <a href="http://pixopoint.com/premium_support/">Premium Support</a> member
* Corrected language support setup
* WP Page URL support confirmed (bugs were reported previously)
* Removed link to Andrew Rickman from credits page since his site is up for sale now and is no longer updated
= 0.6.8 Beta =
* Corrected text error in help section
= 0.6.7 Beta =
* New CSS classes added for dropdowns
* .haschildren class used in more places
= 0.6.6 Beta =
* Beta - Re-includes support for removing WP Page URLs
= 0.6.5 =
* Released as stable version
* Fixed minor 'Page order' bug
= 0.6.4 Beta =
* Changed wp_page_menu() to only be used for 'Auto-theme support' option
* Added 'Compatibility mode' option (strips jQuery features to prevent clashes with plugins and themes which do not enqueue their scripts correctly)
= 0.6.3 Beta =
* Had to remove "remove URLs for specific IDs" option due to serious bug. This feature did not work with permalinks on. We are working on a solution and will release a new version which corrects this problem eventually. Apologies for the error.
= 0.6.2 Beta =
* Added support for wp_page_menu()
* Removed all mentions of the pixopoint_menu() function since it is no longer needed (note: support for this function will be continued indefinitely, so no need to change it if you don't want to)
= 0.6.1 Beta =
* Bug fix for Pages with excluded links (added # for URL)
= 0.6.0 Beta =
* Adds new option in the pages pulldown to remove the URLs for specific IDs
* Feature addition was performed for one of our <a href="http://pixopoint.com/premium_support/">Premium Support members</a>
* Useful upgrade for those wanting to remove links for page parents
= 0.5.10 Beta =
* Removed keyboard accessibility option as it was not allowing dropdowns to appear
= 0.5.9 Beta =
* Fixed major page order bug
* Removed ascending and descending page order options (they don't work with the built in page order system)
= 0.5.8 Beta =
* Confirmed support for WordPress version 2.8.2
* Descending page order bug fixed
* "Categories with posts" bug fixed
* Added new item to uninstaller
= 0.5.7 Beta =
* Note: descending page bug still not fixed
* Can now edit colour hex codes directly
* Can now edit image URLs directly
* Fixed widget pulldown bug
* Added quote marks around font families containing white space
= 0.5.6 Beta =
* Fixed descending pages bug
= 0.5.5 Beta =
* Upgraded to coding engine 0.4alpha
= 0.5.4 Beta =
* Moved javascript to footer
* Added credit to Andy Mortia in admin page
= 0.5.3 Beta =
* Corrected link to plugin page
= 0.5.2 Beta =
* Added built in background image options
* Fixed save design feature
* Prevented jQuery scripts from loading unnecessarily
* Added dialog boxes for colour picker
= 0.5.1 Beta =
* Release to WordPress plugin repository
= 0.5 Beta =
* Numerous minor bug fixes
* Improved contrast in widget graphics 'on hover'
= 0.4.13 Alpha =
* Improved documentation in readme.txt
* Added new screenshots for readme.txt
= 0.4.12 Alpha =
* Bug fixes for design loading system
= 0.4.11 Alpha =
* Initial CSS loaded so that it menu appears on first page load
* 'Continue' text improved for loading designs
* 'Load Editor' button restyled
= 0.4.10 Alpha =
* Fixed colour picker bug
* Improvements to editing panel interface
= 0.4.9 Alpha =
* Confirmed support for WordPress 2.8.1 beta
* Stopped design loader wiping other menus design
* Added license notice in design files
= 0.4.8 Alpha =
* Added many new designs
* Added ability to load new design for each menu
* Fixed letter-spacing bug
* Improved look of buttons on save/open tab
* Tabulated new designs
* Added new graphical backgrounds
= 0.4.7 Alpha =
* Fixed initial page load bug in editor
* Added support for updated coding engine
* Improved uninstaller
* Added quick uninstaller (temp.php) for testing purposes
= 0.4.6 Alpha =
* Improved code comments
* Some functionality now broken
* Removed maintenance.php file
* Registered options only used in the editing panel
= 0.4.5 Alpha =
* Moved Farbtastic script to the scripts folder
= 0.4.4 Alpha =
* Fixed 'My Page Order plugin'
* Fixed Farbtastic jQuery plugin
* Fixed tooltip for Farbtastic
* Added hex colour code validation
* Added credit to froman18
* Lots of bug fixes
= 0.4.3 Alpha =
* Lots of bug fixes
= 0.4.2 Alpha =
* Added in Malcalevaks' code
= 0.4.1 Alpha =
* Removed Malcalevaks index.php suggestion
= 0.4 Alpha =
* Fixed major CSS bug, now works in Opera and Firefox
= 0.3 Pre-alpha =
* Fixed sortables scripts
= 0.2 Pre-alpha =
* Added broken support for 'My Page Order' integration
* Added drag and drop widget system
* Redesigned UI
= 0.1 Pre-alpha =
* Initial test plugin

== Credits ==

Thanks to the following (in no particular order) for help with the development of this plugin:<br />

* <a href="http://www.inakirodriguez.com/">Iñaki Rodriguez</a> - Security reports<br />
* <a href="http://themehybrid.com/">Justin Tadlock</a> - Explained what the wp_page_menu() function is used for<br />
* <a href="http://themehybrid.com/">Justin Tadlock</a> - Explained what the wp_page_menu() function is used for<br />
* <a href="http://blog.mortia.org.uk/index.php/2009/07/16/pixopoint-menu-widget/">Andy Mortia</a> - Created the PixoPoint Menu widget<br />
* <a href="http://transientmonkey.com/">malcalevak</a> - Code contributions utilized from the Multi-level Navigation plugin<br />
* <a href="http://www.vcsvu.nl/">vcsvu</a> - Code contributions utilized from the Multi-level Navigation plugin<br />
* <a href="http://nv1962.net/">nv1962</a> - Code contributions utilized from the Multi-level Navigation plugin<br />
* <a href="http://www.geekyweekly.com/">froman18</a> - Created the My Page Order plugin utilized within this plugin<br />
* <a href="http://wp-fun.co.uk/">Andrew Rickman</a> - Provided assistance in developing the drag and drop functionality<br />
* <a href="http://pmob.co.uk/">Paul O'Brien</a> - Provide technical expertise in bug fixing the CSS coding engine<br />
* <a href="http://wptavern.com/">Jeff Chandler</a> - Created the WP Tavern where much of the development side was sorted out<br />
* <a href="http://instinct.co.nz/">Dan Milward</a> - Provided technical suggestions which led to the development of the plugin<br />

