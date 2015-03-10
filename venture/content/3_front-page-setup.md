Venture Front Page setup
====
![venture Front page setup](http://localhost:8888/builder/joomla-template/data/venture/images/frontpage/venture-frontpage.jpg 'venture Frontpage setup')

Call Me text at top of the page
---
This is a custom html module with the following text.

	{zen-phone}Call Me - +61 0411 266 722{/zen-phone}

The module is called Top Phone number and is published to the top1 position in the quickstart package.

Social icons in left toolbar
---
The social icons on the left of the screen are generated and controlled by the template under the social panel in the template administrator. The color of the icons can be controlled in the theme panel in the template settings under the setting "social icon color". The top offset of the icons is controlled in the social panel in the template settings. Both of these settings take effect after you have compiled less to css.


Top right menu
---
A Joomla menu module is published to top4.

Logo and tagline
---
A custom html module is published to the logo position. The logo is given a width of 12 columns in the template layout settings. The color of the logo is controlled via the template's Theme panel. To generate the logo symbol used in the demo simply add a blank unordered list to the custom html module. The code used in the demo for this module is as follows:

	<ul>
		<li style="text-align: center;"></li>
		<li style="text-align: center;"></li>
		<li style="text-align: center;"></li>
	</ul>
	<h1 style="text-align: center;">VENTURE</h1>
	<p style="text-align: center;">A classic business oriented Joomla design ...</p>
	

Experiment beyond boundaries and open insight 
---
This text is a custom html module published to the banner position. The banner position in this theme is designed to be a simple strip of content - longer pieces of content wont work as well. The banner is automatically placed at the bottom of the slideshow. 

The html used for this module is:
	
	<h2 style="text-align: left;">{zen-circle-o-notch}<span style="line-height: 1.42857143;">{/zen-circle-o-notch}Experiment beyond boundaries and open insight</span><span style="line-height: 1.42857143;">...</span><a class="btn-mini btn btn-primary" href="#">Today</a></h2>

Background slideshow
---
The background slideshow that fills the entire area of the top of the template is generated via the template settings. The slideshow characteristics can be adjusted in the template settings under the effects panel in the template admin. 

To load a single image in the slideshow select a folder in the dropdown list that only contains a single image. 
To display multiple images in the slideshow select a folder on your server that contains multiple images.

The template provides control over the slideshow duration and the time it take to transition between slides. If you would prefer to not display an image in this area simply disable the slideshow in the effects panel in the template settings. The color that fills this area can also be controlled via the template settings under the setting called banner overlay in the Theme panel.


Featured, Get to know us Find Us
---
The content displayed here comes from 3 different modules all published to the tabs position. Any module published to the tabs position is displayed in a tabbed layout.

Featured
----
This module is an instance of the zentools module using the grid layout

Get to know us
----
This is a custom html module.

Find Us 
----
This is an instance of the JB Maps2 module.


Trending
---
This is an instance of the zentools module using the slideshow layout.

In the news
----
This is an instance of the zentools module using a grid layout.

This is who we are
---
This is a custom html module using published to the sidebar2 position using the "overlay-title" module class suffix.

Make a booking
---
This is a custom html module using dummy form markup to show you what a form in that position would look like.

Powerful Services
---
This is a custom html module published to the sidebar2 position.

We build beautiful experiences for creative people
---
This is a custom html module published to the grid13 position. The content used for this module is as follows:


	<p>{zen-desktop}{/zen-desktop}      {zen-tablet}{/zen-tablet}      {zen-mobile}{/zen-mobile}</p>
	<p>Curabitur et erat porta, dictum justo vitae, porttitor mauris. Proin commodo condimentum facilisis. Pellentesque eget sapien in leo aliquet aliquet. <br />Duis lacus ipsum, vehicula sed justo id, pretium accumsan lacus. In sed luctus eros. In id suscipit metus. Quisque porttitor nisl eget nulla semper tincidunt. Aenean diam tellus, maximus in egestas id, feugiat eget sem.</p>
	
Ventures underatken this year
---
This is an instance of the Skillset module published to the grid17 position.

Stunning representations of stoic righteousness
---
This is an custom html module published to the grid21 position. The html used for this module is:

	<p>Curabitur et erat porta, dictum justo vitae, porttitor mauris. Proin commodo condimentum facilisis. Pellentesque eget sapien in leo aliquet aliquet. <br />Duis lacus ipsum, vehicula sed justo id, pretium accumsan lacus. In sed luctus eros. In id suscipit metus. Quisque porttitor nisl eget nulla semper tincidunt. Aenean diam tellus, maximus in egestas id, feugiat eget sem.</p>
	<p style="text-align: center;"><a class="btn btn-primary" href="#">Take action now</a></p>
	
About Us, Popular Items, new items, get to know us
---
All of these items are custom html modules published to the bottom1, bottom2, bottom3 modules positions respectively.


Footer menu
---
A core Joomla menu is published to the footer position. The footer position uses fixed styling which means that it sticks to the bottom of the browser as the user scrolls down the page.