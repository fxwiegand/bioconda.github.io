:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-compcoder'
.. highlight: bash

bioconductor-compcoder
======================

.. conda:recipe:: bioconductor-compcoder
   :replaces_section_title:
   :noindex:

   RNAseq data simulation\, differential expression analysis and performance comparison of differential expression methods

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/compcodeR.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-compcoder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-compcoder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-compcoder/meta.yaml>`_

   This package provides extensive functionality for comparing results obtained by different methods for differential expression analysis of RNAseq data. It also contains functions for simulating count data. Finally\, it provides convenient interfaces to several packages for performing the differential expression analysis. These can also be used as templates for setting up and running a user\-defined differential analysis workflow within the framework of the package.


.. conda:package:: bioconductor-compcoder

   |downloads_bioconductor-compcoder| |docker_bioconductor-compcoder|

   :versions:
      
      

      ``1.26.1-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-1``,  ``1.20.0-0``,  ``1.18.1-0``,  ``1.18.0-0``

      

   
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-catools: 
   :depends r-gdata: 
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-gtools: 
   :depends r-kernsmooth: 
   :depends r-knitr: ``>=1.2``
   :depends r-lattice: ``>=0.16``
   :depends r-markdown: 
   :depends r-mass: 
   :depends r-modeest: 
   :depends r-rocr: 
   :depends r-sm: 
   :depends r-stringr: 
   :depends r-vioplot: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-compcoder

   and update with::

      conda update bioconductor-compcoder

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-compcoder:<tag>

   (see `bioconductor-compcoder/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-compcoder| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-compcoder.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-compcoder
   :alt:   (downloads)
.. |docker_bioconductor-compcoder| image:: https://quay.io/repository/biocontainers/bioconductor-compcoder/status
   :target: https://quay.io/repository/biocontainers/bioconductor-compcoder
.. _`bioconductor-compcoder/tags`: https://quay.io/repository/biocontainers/bioconductor-compcoder?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-compcoder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-compcoder/README.html