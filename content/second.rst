Second post with sophisticated features
#######################################

:date: 2016-11-15 10:20
:modified: 2016-11-15 10:20
:tags: awesome, omg
:category: extra
:slug: extra-post
:authors: wsk
:summary: Test of restructured text

.. contents:: Table of Contents

This is a big title
===================
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

This is first subtitle
----------------------

This is a subsection
~~~~~~~~~~~~~~~~~~~~

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

This is another subsection
~~~~~~~~~~~~~~~~~~~~~~~~~~

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

	Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

This is a second subtitle
-------------------------

And it's this subtitle's subsection
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

This is another big title
=========================

Subtitle
--------

This is a second page with examples of rst

  This is an intendent paragraph
  and the next line of this paragraph.

This is an another paragraph with some **bold** and *italics* text.

In this paragraph i'm going to use lists. Rst comes whith  numbered and bullet lists. I can use nested lists, too.

1. First item

2. Second item

* row
* row
* row
* your
* boat
* one
 
 - two
 - three
  
  + four
  + five
   
- six
- seven
  
* eight
* nine

3. Example of source code
  
.. code-block:: python

 print("Pelican is a static site generator.")
 def foo():
   print "I'm inside foo"
   return 'Huray'
	
 def bar():
     pass
	
.. code-block:: js

 function(e,t){
     var n=void 0,r=void 0;
     return r=e.getAttribute("class").trim().split(" ")
 }
   
4. Images and raw html
 
Here is an example of a static image (centered):
 
.. image:: {filename}/images/bird.jpg
  :alt: a bird
  :align: center
   
and this is an raw html (text and image):

.. raw:: html
   
 <p> I need a feature, so that I can put some direct HTML in the blog articles written in <b>rst</b> format. I also want those htmls to be rendered.</p>
   
  
.. raw:: html
  
 <img src="http://docs.opencv.org/trunk/opencv-logo-small.png" alt="opencv logo"></img>
  
It's amazing, but you  have to remember about blank lines under 'raw' tags
  
