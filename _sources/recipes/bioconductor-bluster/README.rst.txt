:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bluster'
.. highlight: bash

bioconductor-bluster
====================

.. conda:recipe:: bioconductor-bluster
   :replaces_section_title:
   :noindex:

   Clustering Algorithms for Bioconductor

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/bluster.html
   :license: GPL-3
   :recipe: /`bioconductor-bluster <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bluster>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bluster/meta.yaml>`_

   Wraps common clustering algorithms in an easily extended S4 framework. Backends are implemented for hierarchical\, k\-means and graph\-based clustering. Several utilities are also provided to compare and evaluate clustering results.


.. conda:package:: bioconductor-bluster

   |downloads_bioconductor-bluster| |docker_bioconductor-bluster|

   :versions:
      
      

      ``1.0.0-2``,  ``1.0.0-1``

      

   
   :depends bioconductor-biocneighbors: ``>=1.8.0,<1.9.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-igraph: 
   :depends r-matrix: 
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bluster

   and update with::

      conda update bioconductor-bluster

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bluster:<tag>

   (see `bioconductor-bluster/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bluster| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bluster.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bluster
   :alt:   (downloads)
.. |docker_bioconductor-bluster| image:: https://quay.io/repository/biocontainers/bioconductor-bluster/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bluster
.. _`bioconductor-bluster/tags`: https://quay.io/repository/biocontainers/bioconductor-bluster?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bluster/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bluster/README.html