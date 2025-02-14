:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qrqc'
.. highlight: bash

bioconductor-qrqc
=================

.. conda:recipe:: bioconductor-qrqc
   :replaces_section_title:
   :noindex:

   Quick Read Quality Control

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/qrqc.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-qrqc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qrqc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qrqc/meta.yaml>`_
   :links: biotools: :biotools:`qrqc`, doi: :doi:`10.1038/nmeth.3252`

   Quickly scans reads and gathers statistics on base and quality frequencies\, read length\, k\-mers by position\, and frequent sequences. Produces graphical output of statistics for use in quality control pipelines\, and an optional HTML quality report. S4 SequenceSummary objects allow specific tests and functionality to be written around the data collected.


.. conda:package:: bioconductor-qrqc

   |downloads_bioconductor-qrqc| |docker_bioconductor-qrqc|

   :versions:
      
      

      ``1.44.0-1``,  ``1.44.0-0``,  ``1.42.0-0``,  ``1.40.0-0``,  ``1.38.0-1``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``,  ``1.30.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-biovizbase: ``>=1.38.0,<1.39.0``
   :depends bioconductor-rhtslib: ``>=1.22.0,<1.23.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-brew: 
   :depends r-ggplot2: 
   :depends r-plyr: 
   :depends r-reshape: 
   :depends r-testthat: 
   :depends r-xtable: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qrqc

   and update with::

      conda update bioconductor-qrqc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qrqc:<tag>

   (see `bioconductor-qrqc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qrqc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qrqc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qrqc
   :alt:   (downloads)
.. |docker_bioconductor-qrqc| image:: https://quay.io/repository/biocontainers/bioconductor-qrqc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qrqc
.. _`bioconductor-qrqc/tags`: https://quay.io/repository/biocontainers/bioconductor-qrqc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qrqc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qrqc/README.html