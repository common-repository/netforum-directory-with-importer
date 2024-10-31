=== Netforum Member Directory ===
Contributors: gkher
Donate link: http://fusiopnspan.com/
Tags: avectra, netforum, Member directory
Requires at least: 3.0.1
Tested up to: 5.9
Stable tag: 1.12
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easy, drag-and-drop tool to create a member directory using information from netFORUM.

== Description ==

netFORUM Single Sign-On by fusionSpan allows users to sign into WordPress using their netFORUM eWeb credentials.  This plugin utilizes netFORUM’s xWeb Web Service API to authenticate users.

The netFORUM Member Directory by fusionSpan allows users to create a member directory on any page within your WordPress site.  Our plugin makes it easy to select which information from netFORUM Pro will be imported into WordPress.  You can easily display a member directory on any WordPress page using the shortcode [member_table].

You can further specify which fields you want to display in the directory by editing the shortcode [member_table display_fields="fields here"].

Supported fields include

* First Name
* Last Name
* Middle Name
* Organization
* Title
* Email
* City
* State
* Address1
* Address2
* Address3
* Country

**Additional Features**   

fusionSpan specializes in building commercial WordPress plugins that enable integrations between your netFORUM database and your WordPress website.  [Contact us](https://www.fusionspan.com/contact-us/) for these additional integrations:

* **Group-based web access**.  Restrict specific site content to members or specific member groups.  Create WordPress User Role groups based on netFORUM fields.
* **Single sign-out**.  Logout of netFORUM eWeb on WordPress log out.

**Website**                   

[Check out some of our other plugins](https://wordpress.org/plugins/search/fusionspan/), or visit our website [https://www.fusionspan.com/](https://www.fusionspan.com/) to learn more about our products and services.

For questions about this plugin, please fill out our [Contact Us form](https://www.fusionspan.com/contact-us/) or email us at [help@fusionspan.com](mailto:help+web@fusionspan.com). 

== Installation ==

1.	Unzip and upload the folder contents of **fs-netforum-directory-with-importer.zip** to the /wp-content/plugins/ directory.
2.	Activate the plugin through the ‘Plugins’ menu in WordPress.
3.	To set up the directory, go to ‘FS Netforum Import’, located under ‘Tools’ in the WordPress Admin Dashboard.
4.	Export your customers from netFORUM as a .csv.  Select ‘Import Netforum Data’ in the plugin menu and follow the page instructions to import your existing data. 
5.	Use the shortcode [member_table] on any page to display the Member Directory.  

== Frequently Asked Questions ==

= Installation Instructions =

1.	Unzip and upload the folder contents of **fs-netforum-directory-with-importer.zip** to the '/wp-content/plugins/' directory.
2.	Activate the plugin through the ‘Plugins’ menu in WordPress.
3.	To set up the directory, go to ‘FS Netforum Import’, located under ‘Tools’ in the WordPress Admin Dashboard.
4.	Export your customers from netFORUM as a .csv.  Select ‘Import Netforum Data’ in the plugin menu and follow the page instructions to import your existing data. 
5.	Use the shortcode [member_table] on any page to display the Member Directory. 
6.  Check license.txt file for the license key required to activate the plugin.

= Why can’t I drag Customer Key, Customer Member Flag or Receive Benefits Flag to the unused box in the import screen? =

To ensure compatibility with our plugins that require these fields, we require Customer Key, Customer Member Flag, and Receive Benefits Flag when importing your netFORUM data.

= What fields can are supported with this plugin? =

Supported fields include:

* First Name
* Last Name
* Middle Name
* Organization
* Title
* Email
* City
* State
* Address1
* Address2
* Address3
* Country
   
= What other shortcodes can I use in this directory? =
The text in the “” can be edited.

* [member_table] - Displays the member directory
* [member_table_url] - Displays a link to a page that would return member data in a JSON format
* [member_table limit=&quot;number&quot;] - Limits the number of records displayed in the directory. By default, all records display in the directory.
* [member_table display_members_only=&quot;0 or 1&quot;] - If 1, displays only records where the customer’s Receives Benefits Flag is true. If 0, displays all customers. By default, all records display in the directory.
* [member_table display_fields=&quot;fields&quot;] - Specify which fields are displayed in the member directory in which order. By default, the display_fields=&quot;first name, last name, title, email, city, state&quot;
* [member_table_ignore_do_not_display_online=&quot;0 or 1&quot;] - If 1, displays all records regardless if the customer’s Ignore Do Not Display Online field is True. By default, the directory displays records where the Ignore Do Not Display Online field is False.
* [member_table color=&quot;&quot; thead_color=&quot;&quot; tfoot_color=&quot;&quot;] - Use thead_color and tfoot_color to update the color of the table header and table footer, respectively. As a shortcut, you can also use color to update the color of both the table header and footer.

Each of these shortcode fields can be combined to style the directory.
Example: [member_table limit=50 display_members_only=1 display_fields=&quot;firstname, email&quot;] will display:

* 50 records
* Member Flag = True
* List only First Name, Email


== Screenshots ==

1. An example of the member directory on a page. 

2. Here is what the import screen looks like.

3. Dragging an item from used to unused.

== Changelog ==

= 1.0.0 =
* Initial Upload

= 1.0.1 =
* Added more functionality to the member_table shortcode.

= 1.0.2 =
* Bug fixes

= 1.0.3 =
* Minor changes

= 1.0.4 =
* Added new shortcode [member_table_url] which when placed on a page, is replaced by a link that returns the members data in
json format

= 1.0.5 =
* Changed import functionality. Now users have to select a file to be uploaded to the server
* Added three new shortcodes fields to the [member_table] shortcode. thead_color, tfoot_color and color which allows for coloring of the 
table header and footer. 

= 1.0.6 =
* Minor addition, added email as an option to import in the import file screen

= 1.0.7 =
* Updated for Wordpress 4.3

== Upgrade Notice ==

No Upgrade Notices
