Image Gallery Exercise
======================

A progressively enhanced JavaScript image gallery. The base markup provides
a single full size image and an unordered list of thumbnail links pointing to
their full size counterparts.

There are no rules for completing the exercise but we encourage you to try
them using plain JavaScript first then again with a library to understand
the difference.

Feel free to modify the HTML and CSS to suite your needs although bear in mind
there a bonus points (if there were points) for keeping the HTML lean.

The example gallery (no JavaScript) can be [found on GitHub](http://aron.github.com/javascript-exercises/gallery/).

Step 1
------

Write the JavaScript for the gallery.

 1. When the user clicks on a thumbnail its full size representation should
replace the current full size image in the gallery.

Think about:

 - How do you find the elements?
 - How do you listen for the click events?
 - How will you update the image?
 - How the gallery will be created, do you call a function to set it up?
 - Will it work with more than one gallery on the page?

Step 2
------

Add more features to the gallery.

 1. When the user clicks a thumbnail it should have a "selected" state.
 2. The user should see a loading spinner while the new image is loading.

Think about:

 - How will you change the state of the button? (Hint: check the CSS).
 - How will the loading spinner be added?

Step 3
------

Build the same gallery using a JavaScript library like jQuery.

Resources
---------

 - Chapter 4 of [DOM Scripting by Jeremy Keith](http://domscripting.com/book/contents/)
