:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hibag'
.. highlight: bash

bioconductor-hibag
==================

.. conda:recipe:: bioconductor-hibag
   :replaces_section_title:
   :noindex:

   HLA Genotype Imputation with Attribute Bagging

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/HIBAG.html
   :license: GPL-3
   :recipe: /`bioconductor-hibag <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hibag>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hibag/meta.yaml>`_
   :links: biotools: :biotools:`hibag`

   Imputes HLA classical alleles using GWAS SNP data\, and it relies on a training set of HLA and SNP genotypes. HIBAG can be used by researchers with published parameter estimates instead of requiring access to large training sample datasets. It combines the concepts of attribute bagging\, an ensemble classifier method\, with haplotype inference for SNPs and HLA types. Attribute bagging is a technique which improves the accuracy and stability of classifier ensembles using bootstrap aggregating and random variable selection.


.. conda:package:: bioconductor-hibag

   |downloads_bioconductor-hibag| |docker_bioconductor-hibag|

   :versions:
      
      

      ``1.26.1-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-1``,  ``1.20.0-0``,  ``1.18.1-0``,  ``1.16.0-0``,  ``1.14.0-0``

      

   
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-rcppparallel: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hibag

   and update with::

      conda update bioconductor-hibag

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hibag:<tag>

   (see `bioconductor-hibag/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hibag| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hibag.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hibag
   :alt:   (downloads)
.. |docker_bioconductor-hibag| image:: https://quay.io/repository/biocontainers/bioconductor-hibag/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hibag
.. _`bioconductor-hibag/tags`: https://quay.io/repository/biocontainers/bioconductor-hibag?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hibag/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hibag/README.html