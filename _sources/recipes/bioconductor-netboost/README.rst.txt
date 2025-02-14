:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-netboost'
.. highlight: bash

bioconductor-netboost
=====================

.. conda:recipe:: bioconductor-netboost
   :replaces_section_title:
   :noindex:

   Network Analysis Supported by Boosting

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/netboost.html
   :license: GPL-3
   :recipe: /`bioconductor-netboost <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-netboost>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-netboost/meta.yaml>`_

   Boosting supported network analysis for high\-dimensional omics applications. This package comes bundled with the MC\-UPGMA clustering package by Yaniv Loewenstein.


.. conda:package:: bioconductor-netboost

   |downloads_bioconductor-netboost| |docker_bioconductor-netboost|

   :versions:
      
      

      ``1.6.0-2``,  ``1.6.0-1``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-1``

      

   
   :depends bioconductor-go.db: 
   :depends bioconductor-impute: ``>=1.64.0,<1.65.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-colorspace: 
   :depends r-dynamictreecut: 
   :depends r-r.utils: 
   :depends r-rcpp: 
   :depends r-rcppparallel: 
   :depends r-wgcna: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-netboost

   and update with::

      conda update bioconductor-netboost

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-netboost:<tag>

   (see `bioconductor-netboost/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-netboost| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-netboost.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-netboost
   :alt:   (downloads)
.. |docker_bioconductor-netboost| image:: https://quay.io/repository/biocontainers/bioconductor-netboost/status
   :target: https://quay.io/repository/biocontainers/bioconductor-netboost
.. _`bioconductor-netboost/tags`: https://quay.io/repository/biocontainers/bioconductor-netboost?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-netboost/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-netboost/README.html