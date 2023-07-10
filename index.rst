:tocdepth: 1

.. sectnum::

.. Metadata such as the title, authors, and description are set in metadata.yaml

.. TODO: Delete the note below before merging new content to the main branch.

.. note::

   **This technote is a work-in-progress.**

Abstract
========

We perform  comparison between two strategies of averaging wavefront information encoded in the intensity of defocal point source images.  The first approach, "pairing", is to estimate wavefront based on pairs of intra and extra-focal donuts from each corner wavefront sensor.  These individual wavefront estimates per donut pair can be aggregated into eg. mean, and thus conveyed to the optical feedback controller as a per-corner wavefront estimate.  Another approach - "stacking" - is to stack donut images in each wavefront sensor before wavefront estimation, thus arriving at a single wavefront estimate from a "stacked" donut image.  We compare these two approaches at providing a single wavefront estimate per sensor as a function of  donut magnitude, and background. 

Add content here
================

Add content here.
See the `reStructuredText Style Guide <https://developer.lsst.io/restructuredtext/style.html>`__ to learn how to create sections, links, images, tables, equations, and more.

.. Make in-text citations with: :cite:`bibkey`.
.. Uncomment to use citations
.. .. rubric:: References
.. 
.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
