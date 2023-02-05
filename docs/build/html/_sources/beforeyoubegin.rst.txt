This is a First Page
========================

You create titles and subtitles or section headers by underlining text with special characters. 

Use the = sign for a page title. Use a hyphen for section/subtitles. Use the other allowed special characters for more sub-headers. You just have to be consistent with the special characters and headers. Pick a few to use and stick with those.

This file demonstrates and tests how to create a new content and do stuff with it in Sphinx.

Let's test a list
-------------------

This is an ordered list.

1. This thing.
2. That thing.
3. Another thing.
4. One last thing.

This is a bullet list. 
----------------------

* Bullet item
* Bullet item
* Bullet item

This is **bold text** and here's an *italics* example.

This is an image
-----------------

 In the source, the command you use is called a directive. In this case, the "image" directive. Note, there's 1 space in and then the directive starts.

 .. image:: /images/beetle.PNG

This is an image with a caption
--------------------------------

 This image uses the "figure" directive, which lets you add a caption.

 .. figure:: /images/beetle.PNG
    :alt: VW bug

    *This is a caption for the image*
