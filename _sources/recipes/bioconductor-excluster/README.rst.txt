:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-excluster'
.. highlight: bash

bioconductor-excluster
======================

.. conda:recipe:: bioconductor-excluster
   :replaces_section_title:
   :noindex:

   ExCluster robustly detects differentially expressed exons between two conditions of RNA\-seq data\, requiring at least two independent biological replicates per condition

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ExCluster.html
   :license: GPL-3
   :recipe: /`bioconductor-excluster <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-excluster>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-excluster/meta.yaml>`_

   ExCluster flattens Ensembl and GENCODE GTF files into GFF files\, which are used to count reads per non\-overlapping exon bin from BAM files. This read counting is done using the function featureCounts from the package Rsubread. Library sizes are normalized across all biological replicates\, and ExCluster then compares two different conditions to detect signifcantly differentially spliced genes. This process requires at least two independent biological repliates per condition\, and ExCluster accepts only exactly two conditions at a time. ExCluster ultimately produces false discovery rates \(FDRs\) per gene\, which are used to detect significance. Exon log2 fold change \(log2FC\) means and variances may be plotted for each significantly differentially spliced gene\, which helps scientists develop hypothesis and target differential splicing events for RT\-qPCR validation in the wet lab.


.. conda:package:: bioconductor-excluster

   |downloads_bioconductor-excluster| |docker_bioconductor-excluster|

   :versions:
      
      

      ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsubread: ``>=2.4.0,<2.5.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-matrixstats: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-excluster

   and update with::

      conda update bioconductor-excluster

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-excluster:<tag>

   (see `bioconductor-excluster/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-excluster| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-excluster.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-excluster
   :alt:   (downloads)
.. |docker_bioconductor-excluster| image:: https://quay.io/repository/biocontainers/bioconductor-excluster/status
   :target: https://quay.io/repository/biocontainers/bioconductor-excluster
.. _`bioconductor-excluster/tags`: https://quay.io/repository/biocontainers/bioconductor-excluster?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-excluster/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-excluster/README.html