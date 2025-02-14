:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hicbricks'
.. highlight: bash

bioconductor-hicbricks
======================

.. conda:recipe:: bioconductor-hicbricks
   :replaces_section_title:
   :noindex:

   Framework for Storing and Accessing Hi\-C Data Through HDF Files

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/HiCBricks.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-hicbricks <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hicbricks>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hicbricks/meta.yaml>`_

   HiCBricks is a library designed for handling large high\-resolution Hi\-C datasets. Over the years\, the Hi\-C field has experienced a rapid increase in the size and complexity of datasets. HiCBricks is meant to overcome the challenges related to the analysis of such large datasets within the R environment. HiCBricks offers user\-friendly and efficient solutions for handling large high\-resolution Hi\-C datasets. The package provides an R\/Bioconductor framework with the bricks to build more complex data analysis pipelines and algorithms. HiCBricks already incorporates example algorithms for calling domain boundaries and functions for high quality data visualization.


.. conda:package:: bioconductor-hicbricks

   |downloads_bioconductor-hicbricks| |docker_bioconductor-hicbricks|

   :versions:
      
      

      ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rhdf5: ``>=2.34.0,<2.35.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-curl: 
   :depends r-data.table: 
   :depends r-digest: 
   :depends r-ggplot2: 
   :depends r-jsonlite: 
   :depends r-r.utils: 
   :depends r-r6: 
   :depends r-rcolorbrewer: 
   :depends r-readr: 
   :depends r-reshape2: 
   :depends r-scales: 
   :depends r-stringr: 
   :depends r-tibble: 
   :depends r-viridis: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hicbricks

   and update with::

      conda update bioconductor-hicbricks

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hicbricks:<tag>

   (see `bioconductor-hicbricks/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hicbricks| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hicbricks.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hicbricks
   :alt:   (downloads)
.. |docker_bioconductor-hicbricks| image:: https://quay.io/repository/biocontainers/bioconductor-hicbricks/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hicbricks
.. _`bioconductor-hicbricks/tags`: https://quay.io/repository/biocontainers/bioconductor-hicbricks?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hicbricks/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hicbricks/README.html