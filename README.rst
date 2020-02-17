==============================================================================
Hello world!
==============================================================================

This is a test for delivering a README in the ReST format.

.. contents::


And a ``toctree`` alternative:

.. toctree::
   :maxdepth: 2
   :numbered: 0

.. _section1:

------------------------------------------------------------------------------
Section 1
------------------------------------------------------------------------------

Let's try some code:

.. code-block:: console

   $ python -m SimpleHTTPServer 8888

.. _section 11:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Subsection 1.1
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Let's try making links:

* a local link with regular syntax to :ref:`section 1 <section1>` above
* a local link with global syntax to `section 1 <section1>`_ above
* an absolute link to `GitHub home page <https://github.com>`_
* plain text automatically converted to an absolute link https://github.com

******************************************************************************
Subsection 1.1.1
******************************************************************************

ToDo check list:

-  [X] Try sections and subsections -- ok, 3 levels supported; what about 4?
-  [X] Try automatic TOC -- ok, but poor auto text control
-  [X] Try linking -- nok for local links
-  [X] Try code blocks -- ok for console; what about specific langs and customizes like ``tarantoolsession``?
-  [ ] Try check lists -- testing now
-  [ ] Try tables

To be continued...
