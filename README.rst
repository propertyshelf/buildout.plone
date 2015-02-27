Plone buildout extensions
=========================

.. contents:: Content
   :depth: 2

This repository contains a number of configuration files which extend development buildouts for Plone based on `buildout.plonetest`_.
The intended usage is to create a ``buildout.cfg`` like::

    [buildout]
    extends =
        https://raw.githubusercontent.com/propertyshelf/buildout.plone/master/themepreview.cfg
        https://raw.githubusercontent.com/collective/buildout.plonetest/master/test-4.x.cfg
    package-name = ps.diazo.example


.. _`buildout.plonetest`: https://github.com/collective/buildout.plonetest
