.. Sphinx Test documentation master file, created by
   sphinx-quickstart on Sat Feb  4 12:24:08 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Hello World
============

Welcome to my Sphinx testing and demo site.

.. The toc uses the "hidden" option. This hides it from the homepage/landing page. I don't want a TOC on the landing page.

.. toctree::
   :hidden:

.. toctree::
   :maxdepth: 2
   :caption: Topic Types

   beforeyoubegin
   OneMore

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Style Elements

   file2
