:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tscan'
.. highlight: bash

bioconductor-tscan
==================

.. conda:recipe:: bioconductor-tscan
   :replaces_section_title:
   :noindex:

   Tools for Single\-Cell Analysis

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/TSCAN.html
   :license: GPL(>=2)
   :recipe: /`bioconductor-tscan <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tscan>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tscan/meta.yaml>`_
   :links: biotools: :biotools:`tscan`, doi: :doi:`10.1093/nar/gkw430`

   Provides methods to perform trajectory analysis based on a minimum spanning tree constructed from cluster centroids. Computes pseudotemporal cell orderings by mapping cells in each cluster \(or new cells\) to the closest edge in the tree. Uses linear modelling to identify differentially expressed genes along each path through the tree. Several plotting and interactive visualization functions are also implemented.


.. conda:package:: bioconductor-tscan

   |downloads_bioconductor-tscan| |docker_bioconductor-tscan|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.28.0-1</code>,  <code>1.28.0-0</code>,  <code>1.26.0-0</code>,  <code>1.24.0-0</code>,  <code>1.22.0-1</code>,  <code>1.22.0-0</code>,  <code>1.20.0-0</code>,  <code>1.18.0-0</code>,  <code>1.16.0-0</code>,  </span></summary>
      

      ``1.28.0-1``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-delayedarray: ``>=0.16.0,<0.17.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-combinat: 
   :depends r-fastica: 
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-igraph: 
   :depends r-matrix: 
   :depends r-mclust: 
   :depends r-mgcv: 
   :depends r-plyr: 
   :depends r-shiny: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tscan

   and update with::

      conda update bioconductor-tscan

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tscan:<tag>

   (see `bioconductor-tscan/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tscan| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tscan.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tscan
   :alt:   (downloads)
.. |docker_bioconductor-tscan| image:: https://quay.io/repository/biocontainers/bioconductor-tscan/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tscan
.. _`bioconductor-tscan/tags`: https://quay.io/repository/biocontainers/bioconductor-tscan?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tscan/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tscan/README.html