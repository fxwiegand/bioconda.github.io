:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tcc'
.. highlight: bash

bioconductor-tcc
================

.. conda:recipe:: bioconductor-tcc
   :replaces_section_title:
   :noindex:

   TCC\: Differential expression analysis for tag count data with robust normalization strategies

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/TCC.html
   :license: GPL-2
   :recipe: /`bioconductor-tcc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tcc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tcc/meta.yaml>`_
   :links: biotools: :biotools:`tcc`

   This package provides a series of functions for performing differential expression analysis from RNA\-seq count data using robust normalization strategy \(called DEGES\). The basic idea of DEGES is that potential differentially expressed genes or transcripts \(DEGs\) among compared samples should be removed before data normalization to obtain a well\-ranked gene list where true DEGs are top\-ranked and non\-DEGs are bottom ranked. This can be done by performing a multi\-step normalization strategy \(called DEGES for DEG elimination strategy\). A major characteristic of TCC is to provide the robust normalization methods for several kinds of count data \(two\-group with or without replicates\, multi\-group\/multi\-factor\, and so on\) by virtue of the use of combinations of functions in depended packages.


.. conda:package:: bioconductor-tcc

   |downloads_bioconductor-tcc| |docker_bioconductor-tcc|

   :versions:
      
      

      ``1.30.0-1``,  ``1.30.0-0``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-1``,  ``1.22.0-0``,  ``1.20.1-0``,  ``1.18.0-0``

      

   
   :depends bioconductor-bayseq: ``>=2.24.0,<2.25.0``
   :depends bioconductor-deseq2: ``>=1.30.0,<1.31.0``
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-roc: ``>=1.66.0,<1.67.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tcc

   and update with::

      conda update bioconductor-tcc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tcc:<tag>

   (see `bioconductor-tcc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tcc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tcc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tcc
   :alt:   (downloads)
.. |docker_bioconductor-tcc| image:: https://quay.io/repository/biocontainers/bioconductor-tcc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tcc
.. _`bioconductor-tcc/tags`: https://quay.io/repository/biocontainers/bioconductor-tcc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tcc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tcc/README.html