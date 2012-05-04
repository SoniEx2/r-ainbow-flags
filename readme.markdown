LGBT-Themed Flair for Reddit communities
========================================

This project contains 15 flags and the CSS necessary to implement them 
as flair for a subreddit, as we have done over at [/r/ainbow](http://www.reddit.com/r/ainbow/).

Go to the bottom of this readme to see what's different in this fork.

Instructions
------------

Steps 1-2 will happen on this page: 
http://www.reddit.com/r/yoursubreddit/about/stylesheet

Steps 3-4 will happen on this page: 
http://www.reddit.com/r/yoursubreddit/about/flair/

1. Under the "images" section, upload each of the PNG's in this folder. 
   Reddit will suggest a name in the "new image name" box. Keep that 
   name, or you'll have to change the CSS a bit. 
2. Paste the CSS from "flags.css" into the bottom of your stylesheet.
3. Go to the flair page mentioned above, and click on the "Edit Flair
   Templates" tab. There are 16 CSS classes to enter by default; all 
   will have an empty "flair text" box, and "user can edit?" unchecked. 
   You can use any order, and that will be the order they appear in the 
   sidebar flair picker. The class names are listed below. 
4. (optional) Check off the "allow users to assign their own flair" box
   atop the page if you want people to be able to select their own flags. 
   
Congratulations, you're done!
   
CSS Class Names
---------------

These are the CSS classes you will add to the flair template page. For 
reference, this is /r/ainbow's order as of March 2012: 

 * ainbow
 * trans
 * bi
 * ace
 * genderqueer
 * pan
 * ally
 * none
 * trans-ainbow
 * trans-pan
 * trans-bi
 * trans-ace
 * genderqueer-ainbow
 * genderqueer-pan
 * genderqueer-bi
 * genderqueer-ace

Notes
-----

"None" at position 8 looks good, as it puts all the blended flags
into a second column. The CSS class names are invisible to the end user. 

Thanks to kkress, the flair now supports hover text! If you want to add 
an explanation of the flag or custom text alongside the flag, put it
in the "Flair Text" box. This is entirely optional. 

Blended flags were designed by reddit user WTFcannuck; thanks so much! 

If you have any questions or issues, message joeycastillo on reddit. 

On this fork: Split flags for sexualities and more
-----

This fork modifies the original /r/ainbow flair by josecastillo by adding
24 more flags to the mix, up to a total of 39 flags.

File names and class names have also been unified for consistency, and the
CSS file has been updated accordingly.

A .psd file has been added for easy modification of the current flags.

The original licensing of josecastillo's version applies for this fork.

The new flags added are listed here by class name. On step 3 of the instructions above, you will have to add this classes as well.

* ainbow-bi
* ainbow-pan
* ainbow-ace
* ainbow-straight
* bi-ainbow
* bi-pan
* bi-ace
* bi-straight
* pan-ainbow
* pan-bi
* pan-ace
* pan-straight
* ace-ainbow
* ace-bi
* ace-pan
* ace-straight
* straight-ainbow
* straight-bi
* straight-pan
* straight-ace
* trans-straight
* trans-genderqueer
* genderqueer-straight
* genderqueer-trans

A suggested distribution of the flairs on the flair selection box has been uploaded as 5by8.png.








