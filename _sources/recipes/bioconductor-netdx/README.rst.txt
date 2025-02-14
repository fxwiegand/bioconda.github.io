:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-netdx'
.. highlight: bash

bioconductor-netdx
==================

.. conda:recipe:: bioconductor-netdx
   :replaces_section_title:
   :noindex:

   Network\-based patient classifier

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/netDx.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-netdx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-netdx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-netdx/meta.yaml>`_

   netDx is a general\-purpose algorithm to build a patient classifier from heterogenous patient data. The method converts data into patient similarity networks at the level of features. Feature selection identifies features of predictive value to each class. Methods are provided for versatile predictor design and performance evaluation using standard measures. netDx natively groups molecular data into pathway\-level features and connects with Cytoscape for network visualization of pathway themes. For method details see\: Pai et al. \(2019\). netDx\: interpretable patient classification using integrated patient similarity networks. Molecular Systems Biology. 15\, e8497


.. conda:package:: bioconductor-netdx

   |downloads_bioconductor-netdx| |docker_bioconductor-netdx|

   :versions:
      
      

      ``1.2.2-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-biocfilecache: ``>=1.14.0,<1.15.0``
   :depends bioconductor-clusterexperiment: ``>=2.10.0,<2.11.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-multiassayexperiment: ``>=1.16.0,<1.17.0``
   :depends bioconductor-netsmooth: ``>=1.10.0,<1.11.0``
   :depends bioconductor-rcy3: ``>=2.10.0,<2.11.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-scater: ``>=1.18.0,<1.19.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-bigmemory: 
   :depends r-combinat: 
   :depends r-doparallel: 
   :depends r-foreach: 
   :depends r-ggplot2: 
   :depends r-glmnet: 
   :depends r-httr: 
   :depends r-igraph: 
   :depends r-pracma: 
   :depends r-rappdirs: 
   :depends r-rcolorbrewer: 
   :depends r-reshape2: 
   :depends r-rocr: 
   :depends r-rtsne: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-netdx

   and update with::

      conda update bioconductor-netdx

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-netdx:<tag>

   (see `bioconductor-netdx/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-netdx| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-netdx.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-netdx
   :alt:   (downloads)
.. |docker_bioconductor-netdx| image:: https://quay.io/repository/biocontainers/bioconductor-netdx/status
   :target: https://quay.io/repository/biocontainers/bioconductor-netdx
.. _`bioconductor-netdx/tags`: https://quay.io/repository/biocontainers/bioconductor-netdx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-netdx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-netdx/README.html