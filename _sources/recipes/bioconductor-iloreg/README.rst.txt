:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-iloreg'
.. highlight: bash

bioconductor-iloreg
===================

.. conda:recipe:: bioconductor-iloreg
   :replaces_section_title:
   :noindex:

   ILoReg\: a tool for high\-resolution cell population identification from scRNA\-Seq data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ILoReg.html
   :license: GPL-3
   :recipe: /`bioconductor-iloreg <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-iloreg>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-iloreg/meta.yaml>`_

   ILoReg is a tool for identification of cell populations from scRNA\-seq data. In particular\, ILoReg is useful for finding cell populations with subtle transcriptomic differences. The method utilizes a self\-supervised learning method\, called Iteratitive Clustering Projection \(ICP\)\, to find cluster probabilities\, which are used in noise reduction prior to PCA and the subsequent hierarchical clustering and t\-SNE steps. Additionally\, functions for differential expression analysis to find gene markers for the populations and gene expression visualization are provided.


.. conda:package:: bioconductor-iloreg

   |downloads_bioconductor-iloreg| |docker_bioconductor-iloreg|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-aricode: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cluster: 
   :depends r-cowplot: 
   :depends r-dendextend: 
   :depends r-desctools: 
   :depends r-dorng: 
   :depends r-dosnow: 
   :depends r-dplyr: 
   :depends r-fastcluster: 
   :depends r-foreach: 
   :depends r-ggplot2: 
   :depends r-liblinear: 
   :depends r-matrix: 
   :depends r-paralleldist: 
   :depends r-pheatmap: 
   :depends r-plyr: 
   :depends r-reshape2: 
   :depends r-rspectra: 
   :depends r-rtsne: 
   :depends r-scales: 
   :depends r-sparsem: 
   :depends r-umap: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-iloreg

   and update with::

      conda update bioconductor-iloreg

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-iloreg:<tag>

   (see `bioconductor-iloreg/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-iloreg| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-iloreg.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-iloreg
   :alt:   (downloads)
.. |docker_bioconductor-iloreg| image:: https://quay.io/repository/biocontainers/bioconductor-iloreg/status
   :target: https://quay.io/repository/biocontainers/bioconductor-iloreg
.. _`bioconductor-iloreg/tags`: https://quay.io/repository/biocontainers/bioconductor-iloreg?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-iloreg/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-iloreg/README.html