:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-zellkonverter'
.. highlight: bash

bioconductor-zellkonverter
==========================

.. conda:recipe:: bioconductor-zellkonverter
   :replaces_section_title:
   :noindex:

   Conversion Between scRNA\-seq Objects

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/zellkonverter.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-zellkonverter <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-zellkonverter>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-zellkonverter/meta.yaml>`_

   Provides methods to convert between Python AnnData objects and SingleCellExperiment objects. These are primarily intended for use by downstream Bioconductor packages that wrap Python methods for single\-cell data analysis. It also includes functions to read and write H5AD files used for saving AnnData objects to disk.


.. conda:package:: bioconductor-zellkonverter

   |downloads_bioconductor-zellkonverter| |docker_bioconductor-zellkonverter|

   :versions:
      
      

      ``1.0.3-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-basilisk: ``>=1.2.0,<1.3.0``
   :depends bioconductor-delayedarray: ``>=0.16.0,<0.17.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-matrix: 
   :depends r-reticulate: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-zellkonverter

   and update with::

      conda update bioconductor-zellkonverter

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-zellkonverter:<tag>

   (see `bioconductor-zellkonverter/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-zellkonverter| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-zellkonverter.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-zellkonverter
   :alt:   (downloads)
.. |docker_bioconductor-zellkonverter| image:: https://quay.io/repository/biocontainers/bioconductor-zellkonverter/status
   :target: https://quay.io/repository/biocontainers/bioconductor-zellkonverter
.. _`bioconductor-zellkonverter/tags`: https://quay.io/repository/biocontainers/bioconductor-zellkonverter?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-zellkonverter/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-zellkonverter/README.html