:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-methylumi'
.. highlight: bash

bioconductor-methylumi
======================

.. conda:recipe:: bioconductor-methylumi
   :replaces_section_title:
   :noindex:

   Handle Illumina methylation data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/methylumi.html
   :license: GPL-2
   :recipe: /`bioconductor-methylumi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methylumi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-methylumi/meta.yaml>`_
   :links: biotools: :biotools:`methylumi`, doi: :doi:`10.1186/1471-2164-14-293`

   This package provides classes for holding and manipulating Illumina methylation data.  Based on eSet\, it can contain MIAME information\, sample information\, feature information\, and multiple matrices of data.  An \"intelligent\" import function\, methylumiR can read the Illumina text files and create a MethyLumiSet. methylumIDAT can directly read raw IDAT files from HumanMethylation27 and HumanMethylation450 microarrays. Normalization\, background correction\, and quality control features for GoldenGate\, Infinium\, and Infinium HD arrays are also included.


.. conda:package:: bioconductor-methylumi

   |downloads_bioconductor-methylumi| |docker_bioconductor-methylumi|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>2.36.0-1</code>,  <code>2.36.0-0</code>,  <code>2.34.0-0</code>,  <code>2.32.0-0</code>,  <code>2.30.0-1</code>,  <code>2.28.0-0</code>,  <code>2.26.0-0</code>,  <code>2.24.1-0</code>,  <code>2.22.0-1</code>,  </span></summary>
      

      ``2.36.0-1``,  ``2.36.0-0``,  ``2.34.0-0``,  ``2.32.0-0``,  ``2.30.0-1``,  ``2.28.0-0``,  ``2.26.0-0``,  ``2.24.1-0``,  ``2.22.0-1``,  ``2.22.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-annotate: ``>=1.68.0,<1.69.0``
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-fdb.infiniummethylation.hg19: ``>=2.2.0,<2.3.0``
   :depends bioconductor-genefilter: ``>=1.72.0,<1.73.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-illuminaio: ``>=0.32.0,<0.33.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-minfi: ``>=1.36.0,<1.37.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-lattice: 
   :depends r-matrixstats: 
   :depends r-reshape2: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-methylumi

   and update with::

      conda update bioconductor-methylumi

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-methylumi:<tag>

   (see `bioconductor-methylumi/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-methylumi| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-methylumi.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-methylumi
   :alt:   (downloads)
.. |docker_bioconductor-methylumi| image:: https://quay.io/repository/biocontainers/bioconductor-methylumi/status
   :target: https://quay.io/repository/biocontainers/bioconductor-methylumi
.. _`bioconductor-methylumi/tags`: https://quay.io/repository/biocontainers/bioconductor-methylumi?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-methylumi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-methylumi/README.html