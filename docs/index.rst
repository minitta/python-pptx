python-pptx
===========

Release v\ |version| (:ref:`Installation <install>`)

.. include:: ../README.rst


Feature Support
---------------

|pp| has the following capabilities, with many more on the roadmap:

* Round-trip any Open XML presentation (.pptx file) including all its elements
* Add slides
* Populate text placeholders, for example to create a bullet slide
* Add image to slide at arbitrary position and size
* Add textbox to a slide; manipulate text font size and bold
* Add table to a slide
* Add auto shapes (e.g. polygons, flowchart shapes, etc.) to a slide
* Access and change core document properties such as title and subject

Additional capabilities are actively being developed and added on a release
cadence of roughly once per month. If you find a feature you need that |pp|
doesn't yet have, reach out via the mailing list or issue tracker and we'll see
if we can jump the queue for you to pop it in there :)


User Guide
----------

.. toctree::
   :maxdepth: 1

   user/intro
   user/install
   user/quickstart
   user/use-cases
   user/concepts
   user/autoshape-types


Community Guide
---------------

.. toctree::
   :maxdepth: 1

   community/faq
   community/support
   community/updates


API Documentation
-----------------

.. toctree::
   :maxdepth: 2

   api/presentation
   api/slides
   api/shapes
   api/table
   api/text
   api/exc
   api/util


Contributor Guide
-----------------

.. toctree::
   :maxdepth: 1

   dev/runtests
   dev/development_practices
   dev/philosophy
   dev/analysis/index
   dev/design/index
   dev/packaging
   dev/resources/index