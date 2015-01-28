Focus2 Front Page setup
====
![focus2 Front page setup](http://localhost:8888/builder/joomla-template/data/focus2/images/frontpage/focus2-frontpage.jpg 'focus2 Frontpage setup')

One page menu
---
The Focus2 demo site uses the template in one page mode. This means that a menu is output directly from the template and it's links point to specific rows on the page. Eg the bottom link points to the bottom row of modules. 

You can read more about the using the one page menu <a href="http://docs.joomlabamboo.com/zen-grid-framework-4/menus/one-page.html">here</a>.

Social icons in left toolbar
---
The social icons in the left toolbar are generated and controlled by the template under the social panel in the template administrator.

Thumbnails under the social icons
---
The thumbnails under the social icons are generated via the template administrator in the effects > slideshow panel. All settings for the slideshow can be found in the admin in this panel. The slideshow thumbs can be disabled and the width and height of the thumbnails can also be set in the template settings. To create new thumbnails for your images press the create thumbnail images button in the template admin. 
For more information regarding the template control please review the documentation referring to the slideshow settings. 

Titles under thumbnails
---
The titles for the images shown in the thumbnail can be enabled or disabled in the template administrator.

Download icon
---
A download icon can be prepended to the title of the slideshow. This can be toggled on and off in the template settings.

Slideshow count
---
The count for the slideshow can be enabled or disabled in the template settings.

Pause, play, previous, next, fullscreen icons in the right toolbar
---
Each of these items can be enabled or disabled in the template settings. The fullscreen icon causes the theme to shift into a fullscreen mode which means that the main content, logo and overlay are hidden on the page and the image in the slideshow is displayed.

Top right menu
---
A Joomla menu module is published to top4.

Logo and tagline
---
A custom html module is published to the logo position.

Main banner slideshow
---
The main template slideshow id displayed in the top area of the template that stretches down to the grid1 row of modules. The slideshow here is referenced by the slideshow thumbnails, titles etc as described above.

Over the last 20 years text
---
This text is generated from a custom html module published to the grid9 position. The background image is rendered via the template under the background images panel in the template settings. The option called Grid Block3 images controls this option.

The html used for the module uses shortcode syntax from the Zen Shortcode plugin to render the blocks of content. The markup is as follows:
	<h2>Over the last 20 years I've exhibited in the best photography galleries across the world.</h2>
	<p> </p>
	{zen-row}
		{zen-4}
			<p><em>13th January, 2014</em></p>
		{/zen-4} 
		{zen-8}
			<h2>Highfield Garden</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque blandit odio sed tortor efficitur, quis accumsan nisi aliquet. Nunc scelerisque arcu in tellus egestas facilisis. Suspendisse pellentesque rhoncus elit, nec luctus mauris iaculis tempus.</p>
		{/zen-8}
	{/zen-row} 
	{zen-row}
		{zen-4}
			<p><em>20th March, 20013</em></p>
	{/zen-4} 
	{zen-8}
		<h2>Whiskey-a-go-go</h2>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque blandit odio sed tortor efficitur, quis accumsan nisi aliquet. Nunc scelerisque arcu in tellus egestas facilisis. Suspendisse pellentesque rhoncus elit, nec luctus mauris iaculis tempus.</p>
	{/zen-8}
	{/zen-row} 
	{zen-row}
		{zen-4}
			<p><em>14th October January, 2011</em></p>
		{/zen-4} 
		{zen-8}
			<h2>Mawson's Hut</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque blandit odio sed tortor efficitur, quis accumsan nisi aliquet. Nunc scelerisque arcu in tellus egestas facilisis. Suspendisse pellentesque rhoncus elit, nec luctus mauris iaculis tempus.</p>
		{/zen-8}
	{/zen-row} 
	{zen-row}
		{zen-4}
			<p><em>20th June, 2010</em></p>
		{/zen-4} 
		{zen-8}
			<h2>Equatorial Guinea</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque blandit odio sed tortor efficitur, quis accumsan nisi aliquet. Nunc scelerisque arcu in tellus egestas facilisis. Suspendisse pellentesque rhoncus elit, nec luctus mauris iaculis tempus.</p>
		{/zen-8}
	{/zen-row}

My Work speaks for itself text
---
The title of this text is a custom html module published to the grid13 position. The text is in displayed in an h2 tag.

The images below the title in this area of the template is an instance of the zentools module using a 3 column grid layout. The module is published to the grid13 position. 

The background image underneath the module is referenced in the template under the effects > background image section > Grid Block 4 images.

Make Contact
---
This is an instance of the SP Quick contact module published to the grid17 module position. The Sp Quick contact module is a highly rated Joomla module created by Joomshaper. You can read more about it <a href="http://extensions.joomla.org/extensions/extension/contacts-and-feedback/contact-forms/sp-quick-contact">here</a>


Footer menu
---
A core Joomla menu is published to the footer position. The footer position uses fixed styling which means that it sticks to the bottom of the browser as the user scrolls down the page.