=== Disclosures and Permissions Tabs ===
Contributors: Carike
Tags: disclosures, permissions, privacy, security
Requires at least: 4.9
Tested up to: 5.5
Stable tag: 0.0.2
Requires PHP: 5.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

CODE IS NOT FUNCTIONAL YET.  Experimental plugin.  For discussion / development.  Intended as Feature as a Plugin.

== Description ==

VISION STATEMENT:

* We believe that privacy is a strategic competitive advantage.
* This Feature as a Plugin follows a risk-based, as opposed to a compliance-based approach to privacy choices.
* We firmly believe that if your aim is informed consent and you act in good faith at all times, then you are almost certain to come down on the "right" side of legislation.

MISSION STATEMENT:

Thus far many site owners have relied solely on their user experience / visual elements created by a plugin when choosing which of the many plugins fulfilling a particular function to install. We aim to change that.

* DPT seeks to allow website admins / owners to make more informed choices when comparing plugins by facilitating plugin developers' ability to disclose what information is collected from their site and / or their users in a format that makes it understandable for an average user.
* DPT aims to do this by rationally standardizing privacy options within the WordPress ecosystem.
* DPT was developed with the hope of leveraging unrealized synergies.
* DPT does not directly address https://core.trac.wordpress.org/ticket/48486, which only addresses an additional tab to the plugin page on the WordPress.org repository; however, it does seek to compliment it.
* DPT does not seek to replace the Consent API, however, it does seek to compliment it. You can find the Consent API at: https://github.com/rlankhorst/wp-consent-level-api/blob/master/readme.txt
* DPT hopes to assist in implementing sensible guidelines for plugins to advertise premium offerings, to hopefully enable plugin developers to monetize their content without alienating the user-base.

== Installation ==

The code in this plugin is not yet functional.
Intended for discussion / development only.
Until such time as it is submitted to the WordPress plugin repository, you will need to download a .zip folder via GitHub and upload the .zip folder under your /wp-admin/ plugins menu.

== Frequently Asked Questions ==

= Is this plugin functional? =

No.  This code is not yet functional.  It is intended for discussion and development.

= What does this plugin do? =

This plugin is intended as a Feature as a Plugin, which means it will hopefully be included in WordPress core some day soon.
The DPT plugin creates two sub-menus under the Plugins tab in the /wp-admin/ area; namely Disclosures and Permissions.
The Disclosures tab provides those with "manage options" capabilities with privacy related disclosures.
A copy of such disclosures is also available on the plugin's WordPress.org repository page.
The Permissions tab provides those with "manage options" capabilities with privacy related options.
Site administrators / owners can turn off permissions for marketing; statistics; and / or anonymous statistics on a site-wide basis; or they can do so on a plugin-by-plugin basis; or they can manage individual permissions (e.g. an external network call to example.com by plugin XYZ) on a plugin-by-plugin basis.

= Does this plugin guarantee GDPR compliance? =

No.

== Changelog == 

= 0.0.2. =

For discussion purposes only. Code is not yet functional.

1. Updated readme.text:

1.1. Removed the additional proposed headers 
(in favour of proposing a dislosures.json file,
based on Timothy's suggestion in #49272).

2. Create disclosures-schema.json file:

2.1. Created a disclosures-schema.json file
(see #51092).

3. Create  disclosures.json template:

3.1. Create a template for disclosures
(see #51156).

4. Create illustrative examples for developers:

4.1. Create illustrative examples for developers
(see #51156).

5. Updated repository Wiki.

= 0.0.1. =

For discussion purposes only.  Code is not yet functional.

Updated readme.txt:

"Privacy", "Security", "Accessibility" and "Certifications" sections were removed in favour of headers.
Headers should default to FALSE (when parsed), unless explicitly declared as TRUE.

"Privacy" section:

1. Declaring compatibility with privacy tools:
1.1. Removed "Consent API Compatibility" section;
1.1.1. Added header for "Consent API";
1.2. Removed "Disclosures and Permissions Tabs compatibility" section;
1.2.1. Added header for "Disclosures Tab";

2. Helping the site administrator / owner understand how the plugin communicates with other sites:
2.1. Removed "External Network Calls" sub-section;
2.1.1. Added header for "External Network Calls PHP";
2.1.2. Added header for "External Network Calls JavaScript";
2.1.3. Added header for "External Network Calls CSS";
These were split as they may generally be associated with varying levels of risk.

3. Contractual Terms other than the GNU GPL License that may apply to use of the plugin:
3.1. Removed "Contractual Terms" section;
3.1.1. Added header for "SaaS";
Intended for cases where the plugin requires an account with a third party.
E.g. Accounting software
3.1.2. Added header for "Calls to External APIs";
Intended for cases where an account with the third party is not necessarily required.
E.g. Add To Any Social Sharing Buttons
3.1.3. Added header for "Remote Assets";
Intended for cases where information is fetched from a third party domain.
E.g. external loading of fonts / images / etc.

If the plugin author sets any of these headers as TRUE, they need to provide a comma-separated list to the Terms of Service / license terms for each instance.

4. Helping the site administrator / owner understand how the plugin collects user data:
4.1. Removed "Cookies" sub-section / Added header for "Sets Cookies";

5. Helping the site administrator / owner understand the ways in which the plugin processes / stores user data:
5.1. Removed "Cron Jobs" sub-section;
5.1.1. This remains relevant to the Disclosures and Permissions Tabs, but is excluded from the recommended readme.txt.
5.2. Added header for "Writes to DB";
5.2.1. This is intended for any instance in which the plugin writes to the MySQL / MariaDB database;
5.3. Added header for "Creates Custom Post Type";
5.4. Added header for "Creates Custom Table";
5.5. Added header for "Stores PPI";
Intended for plugins that store Personally Identifiable Information (e.g. creates entries in the user_meta table).

6. Helping the site administrator / owner understand other ways in which the plugin can send user data:
6.2. Removed "Mail" sub-section;
6.2.1. Added header for "Sends e-mails";

7. The site administrator / owner as a customer:
7.1. Removed "Advertising" sub-section;
7.1.1. Added header for "Advertising on Dashboard";
7.1.2. Added header for "Advertising on Plugins List";
7.1.3. Added header for "Advertising on Plugin Settings Page";
7.2. Removed "Credits" sub-section;
7.2.1. Added header for "Asks for Backlinks";

8.1. Removed "Applicable Regulartory Standards" section
8.1.1. Alternatives to be considered and discussed.

"Security" section 

9.1. Removed "Security" section;
9.1.1. "Report this Plugin" button in sidebar recommended (with appropriate measures to help prevent abuse);

"Accessibility" section

10.1. Removed "Accessibility section;
10.1.1. Automated tools are not currently available.
10.1.2. Alternatives to be considered and discussed.

"Certifications" section

11.1. Removed section regarding Certifications;
11.1.1. Added header for "Code Audited by Third Party".

= 0.0.0. =
Version for discussion.  Code is not yet functional.
