:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-degnorm'
.. highlight: bash

bioconductor-degnorm
====================

.. conda:recipe:: bioconductor-degnorm
   :replaces_section_title:
   :noindex:

   DegNorm\: degradation normalization for RNA\-seq data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/DegNorm.html
   :license: LGPL (>= 3)
   :recipe: /`bioconductor-degnorm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-degnorm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-degnorm/meta.yaml>`_

   This package performs degradation normalization in bulk RNA\-seq data to improve differential expression analysis accuracy.


.. conda:package:: bioconductor-degnorm

   |downloads_bioconductor-degnorm| |docker_bioconductor-degnorm|

   :versions:
      
      

      ``1.0.0-2``,  ``1.0.0-1``

      

   
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-doparallel: 
   :depends r-foreach: 
   :depends r-ggplot2: 
   :depends r-heatmaply: 
   :depends r-plotly: 
   :depends r-plyr: 
   :depends r-rcpp: ``>=1.0.2``
   :depends r-rcpparmadillo: 
   :depends r-viridis: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-degnorm

   and update with::

      conda update bioconductor-degnorm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-degnorm:<tag>

   (see `bioconductor-degnorm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-degnorm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-degnorm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-degnorm
   :alt:   (downloads)
.. |docker_bioconductor-degnorm| image:: https://quay.io/repository/biocontainers/bioconductor-degnorm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-degnorm
.. _`bioconductor-degnorm/tags`: https://quay.io/repository/biocontainers/bioconductor-degnorm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-degnorm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-degnorm/README.html