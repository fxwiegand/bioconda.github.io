:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ioniser'
.. highlight: bash

bioconductor-ioniser
====================

.. conda:recipe:: bioconductor-ioniser
   :replaces_section_title:
   :noindex:

   Quality Assessment Tools for Oxford Nanopore MinION data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/IONiseR.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-ioniser <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ioniser>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ioniser/meta.yaml>`_
   :links: biotools: :biotools:`ioniser`, doi: :doi:`10.1038/nmeth.3252`

   IONiseR provides tools for the quality assessment of Oxford Nanopore MinION data. It extracts summary statistics from a set of fast5 files and can be used either before or after base calling.  In addition to standard summaries of the read\-types produced\, it provides a number of plots for visualising metrics relative to experiment run time or spatially over the surface of a flowcell.


.. conda:package:: bioconductor-ioniser

   |downloads_bioconductor-ioniser| |docker_bioconductor-ioniser|

   :versions:
      
      

      ``2.14.0-1``,  ``2.14.0-0``,  ``2.12.0-0``,  ``2.10.0-0``,  ``2.8.0-1``,  ``2.6.0-0``,  ``2.4.0-0``,  ``2.2.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-rhdf5: ``>=2.34.0,<2.35.0``
   :depends bioconductor-shortread: ``>=1.48.0,<1.49.0``
   :depends bioconductor-xvector: ``>=0.30.0,<0.31.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-bit64: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-magrittr: 
   :depends r-stringr: 
   :depends r-tibble: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ioniser

   and update with::

      conda update bioconductor-ioniser

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ioniser:<tag>

   (see `bioconductor-ioniser/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ioniser| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ioniser.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ioniser
   :alt:   (downloads)
.. |docker_bioconductor-ioniser| image:: https://quay.io/repository/biocontainers/bioconductor-ioniser/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ioniser
.. _`bioconductor-ioniser/tags`: https://quay.io/repository/biocontainers/bioconductor-ioniser?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ioniser/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ioniser/README.html