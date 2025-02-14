:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-droplettestfiles'
.. highlight: bash

bioconductor-droplettestfiles
=============================

.. conda:recipe:: bioconductor-droplettestfiles
   :replaces_section_title:
   :noindex:

   Test Files for Single\-Cell Droplet Utilities

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/DropletTestFiles.html
   :license: GPL-3
   :recipe: /`bioconductor-droplettestfiles <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-droplettestfiles>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-droplettestfiles/meta.yaml>`_

   Assorted files generated from droplet\-based single\-cell protocols\, to be used for testing functions in DropletUtils. Primarily intended for storing files that directly come out of processing pipelines like 10X Genomics\' CellRanger software\, prior to the formation of a SingleCellExperiment object. Unlike other packages\, this is not designed to provide objects that are immediately ready for analysis.


.. conda:package:: bioconductor-droplettestfiles

   |downloads_bioconductor-droplettestfiles| |docker_bioconductor-droplettestfiles|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-annotationhub: ``>=2.22.0,<2.23.0``
   :depends bioconductor-experimenthub: ``>=1.16.0,<1.17.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-droplettestfiles

   and update with::

      conda update bioconductor-droplettestfiles

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-droplettestfiles:<tag>

   (see `bioconductor-droplettestfiles/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-droplettestfiles| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-droplettestfiles.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-droplettestfiles
   :alt:   (downloads)
.. |docker_bioconductor-droplettestfiles| image:: https://quay.io/repository/biocontainers/bioconductor-droplettestfiles/status
   :target: https://quay.io/repository/biocontainers/bioconductor-droplettestfiles
.. _`bioconductor-droplettestfiles/tags`: https://quay.io/repository/biocontainers/bioconductor-droplettestfiles?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-droplettestfiles/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-droplettestfiles/README.html