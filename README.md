=====================
===ColorChecker.js===
=====================

Match the colors of the Housestyle with the actual colors in the stylescreen

`<script type="text/javascript" src="path/to/colorchecker.js" ></script>`

Add the file to your scripts with all the accepted color codes.
Then open your browsers console and add the following code:

`new ColorChecker(['#fff','#000','#BADA55','rgb(128,128,128)'])`

Then you will see an Interface with the feedback of a progresbar.
It will hang a little on 99%, don't worry, it's just appending the html.



==========
==TODO'S==
==========
* Still needs support for iframe element color checks.
* Create option to show all the elements of the wrong color
* Create message on 99% that says 'were adding the wrong colors'.
* Success message when there are no wrong colors. (quite a shame of me to focus on errors.)
