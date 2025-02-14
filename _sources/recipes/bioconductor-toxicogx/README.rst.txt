:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-toxicogx'
.. highlight: bash

bioconductor-toxicogx
=====================

.. conda:recipe:: bioconductor-toxicogx
   :replaces_section_title:
   :noindex:

   Analysis of Large\-Scale Toxico\-Genomic Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ToxicoGx.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-toxicogx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-toxicogx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-toxicogx/meta.yaml>`_

   Contains a set of functions to perform large\-scale analysis of toxicogenomic data\, providing a standardized data structure to hold information relevant to annotation\, visualization and statistical analysis of toxicogenomic data.


.. conda:package:: bioconductor-toxicogx

   |downloads_bioconductor-toxicogx| |docker_bioconductor-toxicogx|

   :versions:
      
      

      ``1.0.1-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-coregx: ``>=1.2.0,<1.3.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-assertthat: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-catools: 
   :depends r-data.table: 
   :depends r-downloader: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-magrittr: 
   :depends r-reshape2: 
   :depends r-scales: 
   :depends r-tibble: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-toxicogx

   and update with::

      conda update bioconductor-toxicogx

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-toxicogx:<tag>

   (see `bioconductor-toxicogx/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-toxicogx| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-toxicogx.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-toxicogx
   :alt:   (downloads)
.. |docker_bioconductor-toxicogx| image:: https://quay.io/repository/biocontainers/bioconductor-toxicogx/status
   :target: https://quay.io/repository/biocontainers/bioconductor-toxicogx
.. _`bioconductor-toxicogx/tags`: https://quay.io/repository/biocontainers/bioconductor-toxicogx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-toxicogx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-toxicogx/README.html