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
- AuxTel
- Villa Pachon


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





















.. Do not include the document title (it's automatically added from metadata.yaml).

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib

..    :style: lsst_aa
