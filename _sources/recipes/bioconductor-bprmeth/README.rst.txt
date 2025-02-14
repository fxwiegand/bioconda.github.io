:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bprmeth'
.. highlight: bash

bioconductor-bprmeth
====================

.. conda:recipe:: bioconductor-bprmeth
   :replaces_section_title:
   :noindex:

   Model higher\-order methylation profiles

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/BPRMeth.html
   :license: GPL-3 | file LICENSE
   :recipe: /`bioconductor-bprmeth <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bprmeth>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bprmeth/meta.yaml>`_

   The BPRMeth package is a probabilistic method to quantify explicit features of methylation profiles\, in a way that would make it easier to formally use such profiles in downstream modelling efforts\, such as predicting gene expression levels or clustering genomic regions or cells according to their methylation profiles.


.. conda:package:: bioconductor-bprmeth

   |downloads_bioconductor-bprmeth| |docker_bioconductor-bprmeth|

   :versions:
      
      

      ``1.16.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-1``,  ``1.8.1-0``

      

   
   :depends bioconductor-biocstyle: ``>=2.18.0,<2.19.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-assertthat: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cowplot: 
   :depends r-data.table: 
   :depends r-doparallel: 
   :depends r-e1071: 
   :depends r-earth: 
   :depends r-foreach: 
   :depends r-ggplot2: 
   :depends r-kernlab: 
   :depends r-magrittr: 
   :depends r-mass: 
   :depends r-matrixcalc: 
   :depends r-mvtnorm: 
   :depends r-randomforest: 
   :depends r-rcpp: ``>=0.12.14``
   :depends r-rcpparmadillo: 
   :depends r-truncnorm: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bprmeth

   and update with::

      conda update bioconductor-bprmeth

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bprmeth:<tag>

   (see `bioconductor-bprmeth/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bprmeth| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bprmeth.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bprmeth
   :alt:   (downloads)
.. |docker_bioconductor-bprmeth| image:: https://quay.io/repository/biocontainers/bioconductor-bprmeth/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bprmeth
.. _`bioconductor-bprmeth/tags`: https://quay.io/repository/biocontainers/bioconductor-bprmeth?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bprmeth/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bprmeth/README.html