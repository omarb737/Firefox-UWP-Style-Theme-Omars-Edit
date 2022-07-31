# Firefox UWP Style Omar's Edit

A theme that follows UWP styling. This is a modded version of the Firefox UWP CSS store theme. It is a minimalist-retro theme, with some functions omitted for simplicity.


## Install
 https://github.com/omarb737/Firefox-UWP-Style-Theme-Omars-Edit/blob/master/Firefox-UWP-Style-Theme-Omars-Edit.zip

## Copy the contents of the chrome folder to your firefox profile chrome folder.

	1. Go to about:config and accept the risk prompt to continue.
	
	2. Create boolean `uwp.sun-valley`=`true` pref to enable.
	 	
	3. Toggle `toolkit.legacyUserProfileCustomizations.stylesheets` pref to enable.
	
	4. Toggle `layout.css.backdrop-filter.enabled` pref to enable *acrylic blur* in some menus.

	5. Toggle 'browser.tabs.closeTabByDblclick' pref to enable closing tabs by double clicking on them.
	

### Custom CSS

If you want to change any rules use `customChrome.css` and `customContent.css`.

All the theme vars `--uwp-*` can be overridden, Firefox vars too but only if they are not set using `!important`.

### Accent Color

If you want to override the accent color create two new prefs, both string type set to RGB Hex values.

`ui.-moz-accent-color`=`#d13636` Accent color

`ui.-moz-accent-color-foreground`=`#FFFFFF` Text color when the background is the accent color.

### Tips For Using The Minimalist Interface Of The Browser

	- Since this is a minimalist-retro interface, the window controls have been omitted for a sleeker look. Double click on tabs to close them or close them through the taskbar.
	
	- The audio icon has been removed; you can either keep this setting, or remove it in the userChrome.css file where it's labeled with comments.

	- For bookmarks to be displayed as in the previews, create a folder and name it nothing by just entering in a space. You will have to fix this in the 'customize toolbar' settings and position the bookmark bar before the addressbar.


## Screenshots

<picture>
  <img src="https://i.imgur.com/fC6V4vJ.png">
</picture>
<picture>
  <img src="https://i.imgur.com/QzgKM27.png">
</picture>
<picture>
  <img src="https://i.imgur.com/mCwP6i4.png">
</picture>
	



