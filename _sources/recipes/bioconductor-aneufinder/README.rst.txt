:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-aneufinder'
.. highlight: bash

bioconductor-aneufinder
=======================

.. conda:recipe:: bioconductor-aneufinder
   :replaces_section_title:
   :noindex:

   Analysis of Copy Number Variation in Single\-Cell\-Sequencing Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/AneuFinder.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-aneufinder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-aneufinder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-aneufinder/meta.yaml>`_

   AneuFinder implements functions for copy\-number detection\, breakpoint detection\, and karyotype and heterogeneity analysis in single\-cell whole genome sequencing and strand\-seq data.


.. conda:package:: bioconductor-aneufinder

   |downloads_bioconductor-aneufinder| |docker_bioconductor-aneufinder|

   :versions:
      
      

      ``1.18.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-1``,  ``1.12.0-1``,  ``1.10.1-0``

      

   
   :depends bioconductor-aneufinderdata: ``>=1.18.0,<1.19.0``
   :depends bioconductor-bamsignals: ``>=1.22.0,<1.23.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-dnacopy: ``>=1.64.0,<1.65.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cowplot: 
   :depends r-doparallel: 
   :depends r-ecp: 
   :depends r-foreach: 
   :depends r-ggdendro: 
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-mclust: 
   :depends r-reordercluster: 
   :depends r-reshape2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-aneufinder

   and update with::

      conda update bioconductor-aneufinder

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-aneufinder:<tag>

   (see `bioconductor-aneufinder/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-aneufinder| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-aneufinder.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-aneufinder
   :alt:   (downloads)
.. |docker_bioconductor-aneufinder| image:: https://quay.io/repository/biocontainers/bioconductor-aneufinder/status
   :target: https://quay.io/repository/biocontainers/bioconductor-aneufinder
.. _`bioconductor-aneufinder/tags`: https://quay.io/repository/biocontainers/bioconductor-aneufinder?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-aneufinder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-aneufinder/README.html