:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gdsarray'
.. highlight: bash

bioconductor-gdsarray
=====================

.. conda:recipe:: bioconductor-gdsarray
   :replaces_section_title:
   :noindex:

   Representing GDS files as array\-like objects

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/GDSArray.html
   :license: GPL-3
   :recipe: /`bioconductor-gdsarray <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gdsarray>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gdsarray/meta.yaml>`_

   GDS files are widely used to represent genotyping or sequence data. The GDSArray package implements the \`GDSArray\` class to represent nodes in GDS files in a matrix\-like representation that allows easy manipulation \(e.g.\, subsetting\, mathematical transformation\) in \_R\_. The data remains on disk until needed\, so that very large files can be processed.


.. conda:package:: bioconductor-gdsarray

   |downloads_bioconductor-gdsarray| |docker_bioconductor-gdsarray|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.2-0``,  ``1.2.0-1``,  ``1.2.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-delayedarray: ``>=0.16.0,<0.17.0``
   :depends bioconductor-gdsfmt: ``>=1.26.0,<1.27.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-seqarray: ``>=1.30.0,<1.31.0``
   :depends bioconductor-snprelate: ``>=1.24.0,<1.25.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gdsarray

   and update with::

      conda update bioconductor-gdsarray

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gdsarray:<tag>

   (see `bioconductor-gdsarray/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gdsarray| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gdsarray.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gdsarray
   :alt:   (downloads)
.. |docker_bioconductor-gdsarray| image:: https://quay.io/repository/biocontainers/bioconductor-gdsarray/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gdsarray
.. _`bioconductor-gdsarray/tags`: https://quay.io/repository/biocontainers/bioconductor-gdsarray?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gdsarray/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gdsarray/README.html