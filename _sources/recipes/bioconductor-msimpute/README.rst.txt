:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-msimpute'
.. highlight: bash

bioconductor-msimpute
=====================

.. conda:recipe:: bioconductor-msimpute
   :replaces_section_title:
   :noindex:

   Imputation of label\-free mass spectrometry peptides

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/msImpute.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-msimpute <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msimpute>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msimpute/meta.yaml>`_

   MsImpute is a package for imputation of peptide intensity in proteomics experiments. It additionally contains tools for MAR\/MNAR diagnosis and assessment of distortions to the probability distribution of the data post imputation. Currently\, msImpute completes missing values by low\-rank approximation of the underlying data matrix.


.. conda:package:: bioconductor-msimpute

   |downloads_bioconductor-msimpute| |docker_bioconductor-msimpute|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-scran: ``>=1.18.0,<1.19.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-fnn: 
   :depends r-matrixstats: 
   :depends r-mvtnorm: 
   :depends r-pdist: 
   :depends r-rdetools: 
   :depends r-reticulate: 
   :depends r-softimpute: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-msimpute

   and update with::

      conda update bioconductor-msimpute

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-msimpute:<tag>

   (see `bioconductor-msimpute/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-msimpute| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-msimpute.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-msimpute
   :alt:   (downloads)
.. |docker_bioconductor-msimpute| image:: https://quay.io/repository/biocontainers/bioconductor-msimpute/status
   :target: https://quay.io/repository/biocontainers/bioconductor-msimpute
.. _`bioconductor-msimpute/tags`: https://quay.io/repository/biocontainers/bioconductor-msimpute?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-msimpute/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-msimpute/README.html