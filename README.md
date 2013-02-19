Galleriffic - a jQuery photo gallery & slideshow plugin
=======================================================

This is a fork of Galleriffic by Trent Foley. The original project can by found at http://www.twospy.com/galleriffic.

There are some outstanding issues which haven't been resolved since 2008, so this is an attempt to resolve those issues as well as enhance the functionality of the plugin for personal use.

Project modification by Jay Hayes (http://iamvery.com)

This fork introduces changes to allow the thumb gallery to be empty when first loaded.  You might need this
if you intend to load the images via ajax.  If you do use ajax, use the append method, followed (after all images have been appended) by the gotoIndex() method.  E.g.

```
   gallery.append(list_item_object);
   gallery.gotoIndex(0);
```


Integration with Fancybox
-------------------------
Check out the Galleriffic integration with Fancybox (http://fancybox.net) at https://github.com/iamvery/galleriffic/tree/v2.1.0.rc2
