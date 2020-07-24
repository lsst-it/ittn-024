..
  Technote content.

  See https://developer.lsst.io/restructuredtext/style.html
  for a guide to reStructuredText writing.

  Do not put the title, authors or other metadata in this document;
  those are automatically added.

  Use the following syntax for sections:

  Sections
  ========

  and

  Subsections
  -----------

  and

  Subsubsections
  ^^^^^^^^^^^^^^

  To add images, add the image file (png, svg or jpeg preferred) to the
  _static/ directory. The reST syntax for adding the image is

  .. figure:: /_static/filename.ext
     :name: fig-label

     Caption text.

   Run: ``make html`` and ``open _build/html/index.html`` to preview your work.
   See the README at https://github.com/lsst-sqre/lsst-technote-bootstrap or
   this repo's README for more info.

   Feel free to delete this instructional comment.

:tocdepth: 1

.. Please do not modify tocdepth; will be fixed when a new Sphinx theme is shipped.

.. sectnum::

.. TODO: Delete the note below before merging new content to the master branch.

.. note::

   **This technote is not yet published.**

   Fibers deployed at the Summit


.. Add content here.

Introduction
============

In the following document and information to be provided, it is related to the installation, the material, and the location of the network points, such as fiber optics.
This document will present information on the location of the points, quantity, and also the location and quantity of fiber filaments per floor.
This document reflects how the physical network of the main building is built and how it is a project still under construction that may undergo changes in the future such as adding connection points and taking out.
The materials used were selected for their quality and properties so that the project in its operation works at its maximum performance
The fiber optic points single-mode cable was installed since in practice there is no transmission limit, only the equipment that transmits.
The UTP S/FTP cable was selected for its properties to work at 10G / base T and all network points will be installed with this type of cable, both for AP and telephone connections.
As for everything that is user cord is with UTP cat 6 cable
On some occasions, the multimode cable will be installed, only on the occasions that the equipment needs it.



Places to treat the document
----------------------------------------

The places covered in this document are as follows:

- Calibration Hill
- Villa Pachon
- Generator Main


This document details the connections for both copper and fiber optic floors.


To repost, all fiber optic connections come form floor 2 in the computer room on rack A7.
In this rack, all optical headers are concentrated to connect different points of the calibration hill and the villa patch.


Calibration Hill
=================

In the calibration hill, we find the following projects.


- Auxtel
- Weather Tower
- DIMM
- All Sky Camera


Exterior Calibracion Hill
---------------------------


These 4 locations are connected by a single mode 24-strand fibers optics caable form the computer room.

A mufa splice was installed in the exteral pullbox on the calibration hill. Where it is separated into 4 cables and each fiber optic cable is routed to each location as the image shows


Calibration Hill image
^^^^^^^^^^^^^^^^^^^^^^^^






As For the numbering of Fibers optics form the 24-strand cable form the main bulding, it is broken down in this way.


- 1 - 12          Fiber optics for AuxTel
- 13-14-15-16     Fiber optics for Weather Tower
- 17-18-19-20     Fiber optics for DIMM
- 21-22-23-24     Fiber optics for All Sky Camera




Calibration Telescope
----------------------


The calibration telescope project contemplates a connection of 12 single mode optical fibers form the computer room in the main bulding.

These fiber optic connections include an optical header inside the AuxTel rack.

The connection type of these fibers are LC full duplex UPC conectores.

The calibration telescope bulding consists of 2 floors.



In the Auxtel Bulding on the floors, it has the following characteristics in terms of materials and numbering of network points.


- 35 Network points in total
- 2 Access points
- 1 Boxed VoIP
- 2 24-port patch panel with modular jack, category 6A
- 1 Optical header with 12 SM OS2 optical fibers and LC Full-Duplex UPC connectors
- 2 24-port switch
- 1 42U rack
- 2 PDUs


Network point diagram at the location of the first and second floors of the rack with the connection components.


First Floor Image:
^^^^^^^^^^^^^^^^^^^







Second Floor Image:
^^^^^^^^^^^^^^^^^^^^




Villa Pachon
=============


The project to connect the sector of the Villa Pachon arose form the need to provide a secure and reliable connection to these sectors.

The idea is to install a 24-strand fibers optics cable form the computer room in rack A7 to the sector of the Villa Pachon.

In Villa Pachon the places to connect and trir respective optical fibers are:


- Rubin Casino     F.O 1-2-3-4
- Water Control    F.O 5-6-7-8 
- Ex-Besalco       F.O 9-10-11-12
- Villa Generator  F.O 13-14-15-16
- Earthcam         F.O 17-18-19-20
- Mirror Shed      F.O 21-22-23-24



Them. Imagen with connections in the sector considered as Villa Pachon project.

The previous imagen shows the finished Villa Pachon project and with Their respective fiber optics.


At this time, project is under contruction and we project thas is should en like this in the drawing.


Villa Pachon Image
--------------------








Main Generator
================


In the project to connect the main generator, it was born form the idea of monitoring it is operation.

It was implemented to install a single mode 24-strand fiber optic cable and to connect a 12-strand optical terminal with LC UPC connector.

A protective box with an industrial switch with 8 ports was also installed.

we took advantage of installing a phone with a protective box and also an access point and a surveillance camera and seeing the generator working in the image.

This connection comes from the second floor of the main building through the first flooe optical terminal ( inside the first floor optical terminal the cable to the generator is spliced with the 12-strand vacant of the first floor optical terminal.



The generator contains the following connections:

- 1 Camera Connection
- 1 Access point Connection
- 1 VoIP Connection
- 1 Monitoring connection to the Generator



It should be noted that these connections were made witch Cat6 and Cat6A cable and it comes directly form the industrial switch ( We do not have a patch panel in this generator project).



Main Generator Image
---------------------














.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib

..    :style: lsst_aa
