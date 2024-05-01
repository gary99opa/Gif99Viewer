# Gif99Viewer
GIF 99 Viewer for V9938/58 Systems by O.P.A.

There was some discussion last week during the Zoom call about viewing GIF files on the /4a and Geneve. So I dusted off some old source code and have released it and uploaded it to the GitHub as per my previous releases.

* GIF99OPA v1.05 by Gary Bowser and Achim Liese
*
* 1989 Source Code Release
* By Oasis Pensive Abacutors
* Via Gary Bowser (GARYOPA)
* Released April 30th, 2024
* Uploaded to ti99.atariage.com
*
* GIF-S    -> GIF/Viewer Main Source Assemble File
* GIF-MAIN -> GIF/Viewer Main Assembly Source Code
* GIF-SUBS -> GIF/Viewer Common Used BL Sub-Routines
* GIF-BLWP -> GIF/Viewer Video and DSR BLWP Routines
* GIF-DATA -> GIF/Viewer Data/Text Block at The End!

Some notes about this release, it is partly based on a plain 9918 GIF Viewer (before V9938 support) by Achim Liese and some sections are missing comments as they were left-over bits from a disassembly, which I had not go thru totally and optimized and updated for V9938 support. There is also a few pieces I forgot what part that Paul Charlton helped out on as well.

Second it is basically designed to load 320x200 256 color GIF's and 640x320 16 color GIF's -- The later format 16 color is hard to generate these days, you need to get a "LowColor" plugin for Paint.net to allow saving in that format these days. Included in the upload is some sample working GIF's of Berry, Gregory, Lou which were taken from the original JPG format uploaded on WHTech under "Users Photos".

Finally, there is no "text listed" for menu control, but it is basically you enter the "drive number" and it catalogs the disk, and displays the first file that is in GIF format (it also seems to handle MYART files as well), and then you can press X to skip to the next image, or E to go back an image, and ENTER to display more info about the image itself, like colors, size, etc. -- When on the "image info" screen, you can use the arrow keys to shift it up or down or left or right, helpful if you wish to view a larger image in the mode it has selected, it will pick either 256x212 (256 colors) or 512x424 (16 colors) depending on the image size. -- Pressing ENTER again will start the loading of the image, and after the image is displayed pressing either Space or Enter will return you to file name picker. -- There is no "slideshow mode" and there is "no boost in speed" by using extra ram or caching or tables, this is simple program all fitted within the 8k >2000 space with buffers in the >A000 space of the 32k, it doesn't use extra ram to make things go faster in displaying the image.

More Info Please See The AtariAge Release Page: https://forums.atariage.com/topic/365816-release-gif-99-viewer-for-v993858-systems-v105-by-opa/

Enjoy!

-=(GaryOPA)=-
​
