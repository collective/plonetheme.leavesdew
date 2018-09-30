====================
plonetheme.leavesdew
====================


Introduction
============

*plonetheme.leavesdew* package is an installable `Plone`_ Theme using the 
**theming** and **packaging** features available in `plone.app.theming`_ 
to make the `CSS Templates`_ theme `Leavesdew`_ easily available in `Plone`.

This theme has been taken from http://www.freecsstemplates.org/
and integrated into as a diazo theme for Plone.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest version (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://github.com/collective/plonetheme.leavesdew/raw/master/plonetheme/leavesdew/static/preview.png


Features
========
- It's an installable Plone Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple `Diazo`_ package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Add Plone site
--------------

Install Plone 4.x with `plone.app.theming`_ and create a Plone site (if you have not already)
with Diazo theming configured.

.. image:: https://github.com/collective/plonetheme.leavesdew/raw/master/screenshot0.png
  :width: 1024px
  :alt: Create a Plone site from ZMI
  :align: center


Zip file
--------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download a `zip file <https://raw.github.com/collective/plonetheme.leavesdew/master/leavesdew.zip>`_.

2. Import the theme from the Diazo theme control panel.

.. image:: https://github.com/collective/plonetheme.leavesdew/raw/master/screenshot1.png
  :width: 1024px
  :alt: Import the Diazo theme zip file
  :align: center

Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.leavesdew`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.leavesdew


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.leavesdew',
    ],

Select theme
~~~~~~~~~~~~

Select and enable the theme from the Diazo control panel.

.. image:: https://github.com/collective/plonetheme.leavesdew/raw/master/screenshot2.png
  :width: 1024px
  :alt: For select the Diazo theme just click on Activate button
  :align: center

That's it!

You should see:

.. image:: https://raw.github.com/collective/plonetheme.leavesdew/master/plonetheme/leavesdew/static/preview.png
  :width: 1024px
  :alt: plonetheme.leavesdew preview
  :align: center


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.leavesdew/issues
- Source Code: https://github.com/collective/plonetheme.leavesdew

Authors
-------

- Giacomo Spettoli (giacomo.spettoli at gmail dot com)


Collaborations
--------------

- Leonardo J. Caballero G. (leonardocaballero at gmail dot com)

- Full Name (mail at mailserver dot com)

You can find an updated list of all the contributors visit: https://github.com/collective/plonetheme.leavesdew/graphs/contributors


License
=======

The project is licensed under the GPLv2.


.. _`Plone`: http://plone.org
.. _`CSS Templates`: http://www.freecsstemplates.org/
.. _`Leavesdew`: http://www.freecsstemplates.org/preview/leavesdew/
.. _`Diazo`: http://diazo.org
.. _`plone.app.theming`: http://pypi.python.org/pypi/plone.app.theming
