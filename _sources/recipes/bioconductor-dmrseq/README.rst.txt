:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-dmrseq'
.. highlight: bash

bioconductor-dmrseq
===================

.. conda:recipe:: bioconductor-dmrseq
   :replaces_section_title:
   :noindex:

   Detection and inference of differentially methylated regions from Whole Genome Bisulfite Sequencing

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/dmrseq.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-dmrseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrseq/meta.yaml>`_

   This package implements an approach for scanning the genome to detect and perform accurate inference on differentially methylated regions from Whole Genome Bisulfite Sequencing data. The method is based on comparing detected regions to a pooled null distribution\, that can be implemented even when as few as two samples per population are available. Region\-level statistics are obtained by fitting a generalized least squares \(GLS\) regression model with a nested autoregressive correlated error structure for the effect of interest on transformed methylation proportions.


.. conda:package:: bioconductor-dmrseq

   |downloads_bioconductor-dmrseq| |docker_bioconductor-dmrseq|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.9-0``,  ``1.2.1-0``

      

   
   :depends bioconductor-annotationhub: ``>=2.22.0,<2.23.0``
   :depends bioconductor-annotatr: ``>=1.16.0,<1.17.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-bsseq: ``>=1.26.0,<1.27.0``
   :depends bioconductor-bumphunter: ``>=1.32.0,<1.33.0``
   :depends bioconductor-delayedmatrixstats: ``>=1.12.0,<1.13.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-locfit: 
   :depends r-matrixstats: 
   :depends r-nlme: 
   :depends r-outliers: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-dmrseq

   and update with::

      conda update bioconductor-dmrseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-dmrseq:<tag>

   (see `bioconductor-dmrseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-dmrseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-dmrseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-dmrseq
   :alt:   (downloads)
.. |docker_bioconductor-dmrseq| image:: https://quay.io/repository/biocontainers/bioconductor-dmrseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-dmrseq
.. _`bioconductor-dmrseq/tags`: https://quay.io/repository/biocontainers/bioconductor-dmrseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-dmrseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-dmrseq/README.html