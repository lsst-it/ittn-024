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

The purpose of this document is to provide information related to the installation, materials used, network point areas, and the number of fiber filaments used per floor. This documentation also reflects how the physical network of the calibration hill, main generator room and Villa Pachon is built by putting an emphasis on the fact that the project is still undergoing construction and will undergo continuous changes in the near future. These changes include additional network points or removing those that are already in place. The materials used for this project were all selected based on their quality and technical properties so that the project can operate at maximum performance in the operations phase.



Current Deployment
==================


Materials Used 
--------------

Fiber:
^^^^^^

Single-mode fiber was selected and installed due to its technical properties hence it provides an unlimited transmission limit. This fiber will only be used for the equipment that functions as a transmitter (TX) and receiver (RX).

In some occasions, multi-mode fiber cable connections will be set up and installed for any technical equipment that requires it.

Copper:
^^^^^^^

It is also noted that UTP S/FTP cables were also selected due to the cable properties and ability to work at 10GBASE-T speeds. All network points were installed with this type of cable, both the access points and telephony connection systems. In regard to end-user devices, UTP CAT6 was setup. 

Component Features 
^^^^^^^^^^^^^^^^^^

.. figure:: /_static/Tabla.PNG
   :name: Tabla
   :width: 700 px
            
            


Areas of interest
=================

- Calibration Hill
- Main Generator room
- Villa Pachon


This document explains briefly the various connections used, both copper and fiber for the areas located in Cerro Pachon.

As a reminder, all fiber optic connections are born inside the second floor of the computer room in rack A7. In this rack, all-optical headers are concentrated and connect to different areas of the calibration hill and villa pachon. 


Calibration Hill
================

The calibration hill is composed of the following areas:

- Auxtel
- Weather Tower
- DIMM
- All Sky Camera


Exterior Calibracion Hill
---------------------------

The areas listed above are all connected with a 24 Fiber optic filament cable that comes from the computer room located in the main building.

A Fiber optic splice enclosure (MUFA) was used on the calibration hill, the fiber optic filaments inside the MUFA were separated into 4 separate fiber optic cables. Each one of these cables was routed towards each location as shown in the image below. 


Calibration Hill image
^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/Colina-Aux.PNG
   :name: Colina
   :width: 700 px


The fiber optic filaments were numbered and broken down the following way:

- (1 - 12)          Fiber optics for AuxTel
- (13-14-15-16)     Fiber optics for Weather Tower
- (17-18-19-20)     Fiber optics for DIMM
- (21-22-23-24)     Fiber optics for All Sky Camera




Calibration Telescope
----------------------
The calibration telescope building consists of two floors, in this area there are 12 single-mode fiber-optic connections that exit the optical splice enclosure (MUFA) located at the calibration hill, these fiber optic connections make their way towards the optical terminal located in the calibration telescope. These fiber-optic connections have an optical header that's located inside the Auxtel rack and utilize LC/UPC full-duplex connectors. 


In the Auxtel building, the floors have the following characteristics in terms of the materials used and the numbering of the various network points. 

Auxtel

- 35 Network points in total
- 2 Access points
- 1 Boxed VoIP
- 2 24-port patch panel with modular jack, category 6A
- 1 Optical header with 12 SM OS2 optical fibers and LC Full-Duplex UPC connectors
- 2 24-port switch
- 1 42U rack
- 2 PDUs


The following network diagram illustrates the connections and components used for both the first and second floor of the Auxtel building utilizing the same rack.


First Floor Image:
^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/AuxTel-1.jpg
   :name: piso1
   :width: 700 px



Second Floor Image:
^^^^^^^^^^^^^^^^^^^^

.. figure:: /_static/AuxTel-2.jpg
   :name: piso2
   :width: 700 px


Main Generator Room
===================

The idea to connect the main generator room was born from the necessity of monitoring the generator during use.

IT installed 24 single-mode fiber optic filaments where 12 of them are connected to the optical terminal located inside the main generator room. As for the other 12 filaments were left available for use in case any other future requirements are born.

It is also important to mention that an industrial 8 port switch was also installed in the main generator room inside a protective box. The purpose of this switch was to set up a phone in case of any emergencies or activities that require its use. Additionally an access point and a camera were set up for surveillance and wifi connectivity all inside the main generator area.

The backbone of this connection comes from the second floor, passes through the optical terminal located on the first floor of the main building, and continues its way towards an optical terminal located inside the main generator room where the box with the switch is located.  


Generator room network components: 

- 1 Camera Connection
- 1 Access point Connection
- 1 VoIP Connection
- 1 Monitoring connection to the Generator

Note: All of these connections were made with CAT6 and CAT6A cables and come directly from the industrial switch located inside the main generator room. 


Main Generator Image
---------------------

.. figure:: /_static/Main-G.PNG
   :name: Generator
   :width: 700 px



Villa Pachon
============

The need to connect Villa Pachon to the computer room located inside the main building arose from the fact that the current connection was not reliable enough in this sector. Additionally, other areas inside the Villa which did not have connectivity were also incorporated into this connection to the computer room. 


To carry out this task, IT installed 24 Fiber Optic filaments backbone cable from the computer room in rack A7 towards the sector known as Villa Pachon in which its divided in to the following areas:

- Rubin Casino     F.O 1-2-3-4      
- Water Control    F.O 5-6-7-8      
- Ex-Besalco       F.O 9-10-11-12   
- Villa Generator  F.O 13-14-15-16  
- Earthcam         F.O 17-18-19-20  
- Mirror Shed      F.O 21-22-23-24

As to this year 2020 the following areas are connected and operational.

- Ex-Besalco      (Completed)     
- Villa Generator (Completed)


Activities planned for FY21/22
==============================

Villa Pachon
------------

For FY21/22 we expect to connect the remaining areas to the 24 Fiber Optic backbone cable.

- Rubin Casino     F.O 1-2-3-4      (Pending)
- Water Control    F.O 5-6-7-8      (Pending)
- Earthcam         F.O 17-18-19-20  (Pending)
- Mirror Shed      F.O 21-22-23-24  (Pending)



The image below illustrates the sector considered as the "Villa Pachon project", it also shows how the project will look like in the future once its finished and all fiber optic connections are setup and installed.


Villa Pachon Image for FY21/22
------------------------------

.. figure:: /_static/Villa-1.PNG
   :name: Villa
   :width: 700 px

Acronyms
========

.. include:: document.rst 

.. .. rubric:: References

.. Make in-text citations with: :cite:`bibkey`.

.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib

..    :style: lsst_aa
