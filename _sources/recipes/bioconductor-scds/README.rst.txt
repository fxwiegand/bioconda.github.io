:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-scds'
.. highlight: bash

bioconductor-scds
=================

.. conda:recipe:: bioconductor-scds
   :replaces_section_title:
   :noindex:

   In\-Silico Annotation of Doublets for Single Cell RNA Sequencing Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/scds.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-scds <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scds>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scds/meta.yaml>`_

   In single cell RNA sequencing \(scRNA\-seq\) data combinations of cells are sometimes considered a single cell \(doublets\). The scds package provides methods to annotate doublets in scRNA\-seq data computationally.


.. conda:package:: bioconductor-scds

   |downloads_bioconductor-scds| |docker_bioconductor-scds|

   :versions:
      
      

      ``1.6.0-1``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-1``

      

   
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dplyr: 
   :depends r-matrix: 
   :depends r-proc: 
   :depends r-xgboost: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-scds

   and update with::

      conda update bioconductor-scds

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-scds:<tag>

   (see `bioconductor-scds/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-scds| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-scds.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-scds
   :alt:   (downloads)
.. |docker_bioconductor-scds| image:: https://quay.io/repository/biocontainers/bioconductor-scds/status
   :target: https://quay.io/repository/biocontainers/bioconductor-scds
.. _`bioconductor-scds/tags`: https://quay.io/repository/biocontainers/bioconductor-scds?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-scds/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-scds/README.html