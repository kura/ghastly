=======
Ghastly
=======

Ghastly is a clean and minimal theme for `Pelican http://getpelican.com>`__
based on the Casper default theme for `Ghost <https://ghost.org/>`__.

Supports Disqus out of the box.

Supports Pygments out of the box.

It DOES NOT support Google Analytics out of the box, because I do not use it. Adding
the tracking script to `base.html` is a simple task though.

Typography
==========

Ghastly uses the `Fira Sans <http://dev.carrois.com/fira-3-1/>`__ font. For 
pre blocks it uses Fira Mono.

Requirements
============

- pelican
- webassets
- cssmin
- pelican webassets

.. code::

    pip install pelican webassets cssmin

You can find pelican webassets at `https://github.com/getpelican/pelican-plugins/tree/master/assets <https://github.com/getpelican/pelican-plugins/tree/master/assets>`__.

Configuration
=============

.. code:: python

    DIRECT_TEMPLATES = (('index', 'archives', '404'))

Screenshots
===========

Homepage
--------

.. image:: https://github.com/kura/ghastly/blob/master/homepage.png

Article
-------

.. image:: https://github.com/kura/ghastly/blob/master/article.png

License
=======

MIT, a copy of the license is in the root of this project.