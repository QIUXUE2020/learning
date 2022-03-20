Welcome to Liqx's documentation!
===================================

.. note::

   This project is used for testing.

Contents
--------

.. toctree::
   :maxdepth: 2
   TextBooks
   Code
   Doc
   docs/预编码技术.docx
Title 1, use "====", how to write rst doc
=========================================
This is title, one rst example.

Title 2, use "----", one table example
--------------------------------------

This is table example.

==== ============================================ =======================  
Verb          URI                                  Description
==== ============================================ =======================
GET  clouds/{cloud_id}/networks          Retrieve list of network extensions
==== ============================================ =======================

Title 3, Query Parameters
+++++++++++++++++++++++++

The following table shows the query parameters for this service.

=========== ================================= ========
Attribute               Description           Required
=========== ================================= ========
osNetworkId      The id of OpenStack network.       No
=========== ================================= ========

Code block need begin with ::
+++++++++++++++++++++++++++++

::
   {undefined
         "name": "Zhang Hua",
         "url":  
       }
List need begin with *
++++++++++++++++++++++

The following attributes are used in the request body:

* ``name``

  Human-readable name. Might not be unique. Optional.

* ``url``

  url value.
