Controlling the Focus2 background slideshow
----

Focus2 comes with the functionality to create a single fullscreen slideshow with thumbnail control as well as up to 7 background slideshows without thumbnail control. The following refers to controlling the slideshow with thumbnail control.

Slideshow the thumbnail control.
---

The slideshow with thumbnail control is controlled via the slideshow settings in the template administrator. This slideshow is output at the top of the page and either stretches to fill the entire page if no other background images are specified or fill the top area of the page down to the first row of grid content - eg any content published to grid1 to grid4.

It is possible to display the following attributes for this slideshow:
- Slideshow thumbnails
- Slideshow title
- Download image icon
- Play / Pause button
- Next Prev buttons
- Fullscreen button

In addition to this it is also possible to control the slideshow duration and the transition speed of the slideshow.

Slideshow Settings
---

![Slideshow settings](../data/focus2/images/slideshow/slideshow-image-source.png)

The initial section of the slideshow settings enables the slideshow and determines the folder on your server where the images are referenced from. 


Slideshow Thumbnail Images
---
![Slideshow Thumbs](../data/focus2/images/slideshow/slideshow-thumbs.png)

The slideshow thumbs allow the user to enable or disable the slideshow thumbs which are displayed on the left of the page underneath the left toolbar / block of colour.

The thumb width and thumb height is used to determine the width and height of the thumbs that are created by the template.

Create thumbnail images button
---
This button is used to create new thumbnail images. The thumbnail images are placed in a subfolder of the original folder of the image that is being resized.

For example if you are resizing images found in the images/myimages folder then a new folder called images/myfolder/thumbs will be automatically created and the images will be saved to this folder.

If the thumbs folder does not exist then the full sized image will be used for the thumbnail image.

When this button is clicked the built in resize script checks first to see if an image of the same size of that image already exists. If it already exists then it will not be generated again.

General Slideshow Options
---
The slideshow options allow the user to enable or disable the various slideshow elements available for display on the page.

Slideshow titles
----
Displays or hides the titles of the images in the slideshow on the left of the page.

Allow download images
----
When enabled a download icon is prepended to the slideshow titles that when clicked will download the currently active image ot the users hard drive.

Display Play / Pause
----
Enables or disables the play / Pause button in the right toolbar area.

Slideshow Count
----
Enables or disables the display of the number of items int he slideshow and the current slideshow being displayed.

Allow Fullscreen mode
----
Enables the display of the fullscreen button that when clicked hides the main content, site logo, and transparent overlay.  In fullscreen mode the title, thumbs and slideshow controls are repositioned to the top of the page. To revert back to the normal mode the fullscreen icon needs to be clicked again to reveal the default display for the template.

Slideshow Duration
----
This option determines the length of time that an image stays on the page before the next image in the slideshow is shown.

Slideshow Transition
----
This option determines how fast the transition to the next image in the slideshow is.
