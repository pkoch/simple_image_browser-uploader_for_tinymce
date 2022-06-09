ROBIT BT plugins for tinyCME editor
===================================

Simple image manager integrated in advimage popu window

- Image galery browser,
- image delete,
- image upload,
- thumbmail generator,
- accept jpg,gif,png, mp3,avi,vmw,mov,mpg extensions,
- accept only one image folder

Required: tinyMCE 3.0,
          advimage plugin,
          PHP4 and gd.lib extension

Installation:

  1. edit galery.php file config section
  2. copy galery.php file into tinyCME/plugins/advimage folder
  3. replace the image.htm in tinyCME/plugins/advimage folder
  4. copy audio.jpg, video.jpg into tinyCME/plugins/advimage folder

licence:
   GNU/GPL
Authot:
   Tibor Fogler  foglert@robitbt.hu  www.robitbt.hu
   2008.04.20

------------------------------------------------
Revision Log:
Rev1: <http://pko.ch>

- Fixed some security issues (files and dir were created with 777. Changed to 644)
- Factored out some path responsibilities.
