# theme_bootstrap4_child

Twitter Bootstrap 4 theme for TYPO3 CMS. Based on theme_bootstrap4

![Screenshot](Meta/Screenshots/screenshot.png)

theme_bootstrap4_child is a very basic theme. It can be used to start your own theme.


## Your steps to use theme_bootstrap4_child
1. Install the following Extension in your TYPO3 8.7.x installation.
	- static_info_tables
	- gridelements
	- themes (Branch 8-0: https://github.com/typo3-themes/themes/tree/8-0)
	- dyncss
	- dyncss_scss
	- theme_bootstrap4 (Branch rebase: https://github.com/typo3-themes/theme_bootstrap4/tree/rebase)
	- theme_bootstrap4_child (Master: https://github.com/typo3-themes/theme_bootstrap4_child)
	
	The extensions depend on each other. If you choose a different order, the dependencies will be displayed and you can resolve them.

2. Template 
	- Create new template for a new site and edit them.
	- You don't need anything in the fields Constants and Setup. Everything will be served with the theme. (Of course you can still use the fields and override the theme configuration.)
	- Add the following Static Includes (required order; do not use fluid_styled_content static template!)
		1. Themes
		2. Gridelements
		3. ... further extensions
	- Chose your theme "Theme-Bootstrap4 Child" under the tab "Themes"

3. Feature
	- After you saved your template, you can chose on the tab "Themes" the desired features and extension.
	- You need at least a backend layout from the group "Theme features". Otherwise your theme will not work.
	- Save your template.
	
4. Page settings
	- Edit your root-page and chose on the tab "Appearance" your desired backend layout. You can chose the default backend layout for the subpages here as well.
	- Set on the tab "Behaviour" your root page as "Use as Root Page"
	- And save the setting on your page.
	
5. Theme configuration
	- Switch to the themes module and be sure you selected your new root page.
	- Chose from the menu "Search" the entry "Site Related Settings" and change options as you wish.
	- Don't forget to save your changes. 

6. Your are ready to use the theme
	- Your next steps could be
		- Change more theme options e.g. Colors, Logo, Page- and Container IDs.
		- Create your page tree
		- change the theme on the code base