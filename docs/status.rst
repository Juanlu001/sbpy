.. _status page:

Status Page
===========

This page indicates the progress on specific modules, classes, and
functions.

While this page is mainly intented for internal purposes, it provides
insight into functionality that is already available and can be
tested.

If you are or have been working on code, please indicate its status
here.


Status per Module
-----------------

`sbpy.data`
~~~~~~~~~~~
maintainer: MM

    * `~sbpy.data.DataClass` 2018/09: basic functionality established, alternative property names implemented; tests and documentation available
    * `~sbpy.data.Names` 2018/09: asteroid and comet name parsing established, asteroid_or_comet implemented; `~sbpy.data.Names.altident` not yet implemented
    * `~sbpy.data.Ephem` 2018/10: jplhorizons and Minor Planet Center queries implemented, OpenOrb ephemeris computation available; imcce, lowell queries tbd
    * `~sbpy.data.Orbit` 2018/09: jplhorizons query implemented, OpenOrb orbit transformations and orbit propagation implemented; mpc, imcce, lowell queries tbd
    * `~sbpy.data.Phys` 2018/09: crude jplsbdb query implemented, no tests or documentation available; lowell query tbd
      
`sbpy.activity`
~~~~~~~~~~~~~~~
maintainer: MSK

    * `~sbpy.activity.dust` 2018/09:
      
      * Halley-Marcus phase function implemented
      * Afρ class: conversion to/from flux density for a specific wavelength is implemented, using a filter bandpass and conversion to/from magnitudes is in development.
      * εfρ class: conversion to/from flux density implemented for a specific wavelength, using a filter bandpass and conversion to/from magnitudes is in development.
      * Syndynes and synchrones are TBD.
	
    * `~sbpy.activity.gas` 2018/09:
      
      * Haser model implemented, final tests TBD.
      * Vectorial model TBD (use source code from M. Festou?).


`sbpy.photometry`
~~~~~~~~~~~~~~~~~
maintainer: JYL, MM

    * 2018/09: disk integrated phase functions implemented: HG, HG12, HG1G2, linear phasecurve
    * 2018/09: Hapke tbd

`sbpy.shape`
~~~~~~~~~~~~
maintainer: MM

    * 2018/09: Kaasalainen shape inversion code tbd
    * 2018/09: lightcurve periodicity tools tbd

`sbpy.spectroscopy`
~~~~~~~~~~~~~~~~~~~
maintainer: MdVB

    * 2018/09: JPL molecular spectral database interface implemented as astroquery.jplspec 
    * 2018/09: some methods preliminarily implemented
    * 2018/10: `~sbpy.spectroscopy.sun` and `~sbpy.spectroscopy.vega` spectral models implemented and fully tested.

`sbpy.thermal`
~~~~~~~~~~~~~~
maintainer: MM

    * 2018/09: STM, FRM, NEATM implementations tbd 

`sbpy.imageanalysis`
~~~~~~~~~~~~~~~~~~~~
maintainer: MSK

    * 2018/09: comet coma image enhancement tools tbd
    * 2018/09: PSF subtraction techniques tbd

`sbpy.obsutil`
~~~~~~~~~~~~~~
maintainer: MSK, MM

    * 2018/09: finder charts, peak observability tbd

`sbpy.bib`
~~~~~~~~~~
maintainer: all

    * 2018/09: basic functionality implemented; `~sbpy.bib.to_bibtex` tbd



last updated: Sep 17, 2018
