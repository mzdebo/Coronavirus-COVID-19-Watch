NO LONGER MAINTAINED ON GITHUB
Maintained on WordPress.org

Browse the code: https://plugins.trac.wordpress.org/browser/coronavirus-covid-19-watch/
Check out the SVN repository: https://plugins.svn.wordpress.org/coronavirus-covid-19-watch/





=== Coronavirus COVID-19 Watch ===
Contributors: mmediagroup

Tags: covid, coronavirus, covid-19
Requires at least: 5.1
Tested up to: 5.2
Requires PHP: 7.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
 
This plugin will get live data with total cases around the world and show it on your dashboard. It will also add a helpful link in the top toolbar to quickly get more info.

== Description ==
 
This plugin will get live data with total cases around the world and show it on your dashboard. It will also add a helpful link in the top toolbar to quickly get more info. It will also add a widget that you can add to your footers or menus.

There's also a shortcode you can use in your posts to always reference the most up to date number of confirmed cases. Use the shortcode [covid-confirmed] in your code to output the current number of confirmed cases. You can pass a country and status, like [covid-confirmed country="France" status="confirmed"] or [covid-confirmed country="US" status="deaths"] to get results only from that country.

This plugin uses data from Johns Hopkins University and ARCGIS, provided via API thanks to M Media (mmediagroup.fr). Here's a link to [M Media](https://mmediagroup.fr/), the API provider. Access the API directly here [M Media](https://covid-api.mmediagroup.fr/v1/cases). The M Media API privacy policy is [here](https://mmediagroup.fr/privacy-policy), the terms of use [here](https://mmediagroup.fr/terms-and-conditions) and the JHU Data Usage policy is [here](https://github.com/CSSEGISandData/COVID-19).

== Features ==

1. 100% free
2. Up to date information from Johns Hopkins University
3. Incredibly fast - no performance impact on your site
4. Shortcodes to have self-updating case numbers in your posts
5. Admin dashboard box showing live confirmed cases
6. Widget for confirmed cases that you can add to your footers or menus

== Installation ==
 
This section describes how to install the plugin and get it working. You can also install it by searching for the "Coronavirus COVID-19 Watch" plugin in the Plugins > Add New.
 
e.g.
 
1. Upload the plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
 
== Frequently Asked Questions ==
 
= Is it free? =
 
Yes, this plugin is free to use.

= Can I show data for my country only? =
 
Yes, you can pass your country in the shortcode attributes.
 
== Screenshots ==
 
1. Example of the dashboard widget in the admin area.
2. Example of how to use the shortcode to get live Coronavirus cases in your posts.
 
== Changelog ==

= 1.0.1 =
* Added attribute "country" and "status" to shortcode.

= 1.0 =
* Initial commit.

== Coming soon ==
* Choose between showing deaths or confirmed cases
* Gutenberg Block
* Menu to allow users to choose settings (like in point 1)
