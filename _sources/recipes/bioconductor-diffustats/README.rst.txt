:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-diffustats'
.. highlight: bash

bioconductor-diffustats
=======================

.. conda:recipe:: bioconductor-diffustats
   :replaces_section_title:
   :noindex:

   Diffusion scores on biological networks

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/diffuStats.html
   :license: GPL-3
   :recipe: /`bioconductor-diffustats <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-diffustats>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-diffustats/meta.yaml>`_
   :links: biotools: :biotools:`diffuStats`, doi: :doi:`10.1093/bioinformatics/btx632`

   Label propagation approaches are a widely used procedure in computational biology for giving context to molecular entities using network data. Node labels\, which can derive from gene expression\, genome\-wide association studies\, protein domains or metabolomics profiling\, are propagated to their neighbours in the network\, effectively smoothing the scores through prior annotated knowledge and prioritising novel candidates. The R package diffuStats contains a collection of diffusion kernels and scoring approaches that facilitates their computation\, characterisation and benchmarking.


.. conda:package:: bioconductor-diffustats

   |downloads_bioconductor-diffustats| |docker_bioconductor-diffustats|

   :versions:
      
      

      ``1.10.2-0``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.4.0-0``,  ``1.2.0-0``,  ``0.104.0-0``,  ``0.102.0-0``

      

   
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-checkmate: 
   :depends r-expm: 
   :depends r-igraph: 
   :depends r-mass: 
   :depends r-matrix: 
   :depends r-plyr: 
   :depends r-precrec: 
   :depends r-rcpp: 
   :depends r-rcpparmadillo: 
   :depends r-rcppparallel: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-diffustats

   and update with::

      conda update bioconductor-diffustats

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-diffustats:<tag>

   (see `bioconductor-diffustats/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-diffustats| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-diffustats.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-diffustats
   :alt:   (downloads)
.. |docker_bioconductor-diffustats| image:: https://quay.io/repository/biocontainers/bioconductor-diffustats/status
   :target: https://quay.io/repository/biocontainers/bioconductor-diffustats
.. _`bioconductor-diffustats/tags`: https://quay.io/repository/biocontainers/bioconductor-diffustats?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-diffustats/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-diffustats/README.html