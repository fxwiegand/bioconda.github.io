:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ggbio'
.. highlight: bash

bioconductor-ggbio
==================

.. conda:recipe:: bioconductor-ggbio
   :replaces_section_title:
   :noindex:

   Visualization tools for genomic data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ggbio.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-ggbio <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ggbio>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ggbio/meta.yaml>`_
   :links: biotools: :biotools:`ggbio`

   The ggbio package extends and specializes the grammar of graphics for biological data. The graphics are designed to answer common scientific questions\, in particular those often asked of high throughput genomics data. All core Bioconductor data structures are supported\, where appropriate. The package supports detailed views of particular genomic regions\, as well as genome\-wide overviews. Supported overviews include ideograms and grand linear views. High\-level plots include sequence fragment length\, edge\-linked interval to data view\, mismatch pileup\, and several splicing summaries.


.. conda:package:: bioconductor-ggbio

   |downloads_bioconductor-ggbio| |docker_bioconductor-ggbio|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.38.0-1</code>,  <code>1.38.0-0</code>,  <code>1.36.0-0</code>,  <code>1.34.0-0</code>,  <code>1.32.0-1</code>,  <code>1.30.0-0</code>,  <code>1.28.5-0</code>,  <code>1.26.0-0</code>,  <code>1.24.1-0</code>,  </span></summary>
      

      ``1.38.0-1``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-1``,  ``1.30.0-0``,  ``1.28.5-0``,  ``1.26.0-0``,  ``1.24.1-0``,  ``1.22.0-0``,  ``1.20.2-0``,  ``1.18.5-0``,  ``1.18.1-0``,  ``1.18.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-annotationfilter: ``>=1.14.0,<1.15.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-biovizbase: ``>=1.38.0,<1.39.0``
   :depends bioconductor-bsgenome: ``>=1.58.0,<1.59.0``
   :depends bioconductor-ensembldb: ``>=2.14.0,<2.15.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-organismdbi: ``>=1.32.0,<1.33.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends bioconductor-variantannotation: ``>=1.36.0,<1.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggally: 
   :depends r-ggplot2: ``>=1.0.0``
   :depends r-gridextra: 
   :depends r-gtable: 
   :depends r-hmisc: 
   :depends r-reshape2: 
   :depends r-rlang: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ggbio

   and update with::

      conda update bioconductor-ggbio

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ggbio:<tag>

   (see `bioconductor-ggbio/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ggbio| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ggbio.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ggbio
   :alt:   (downloads)
.. |docker_bioconductor-ggbio| image:: https://quay.io/repository/biocontainers/bioconductor-ggbio/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ggbio
.. _`bioconductor-ggbio/tags`: https://quay.io/repository/biocontainers/bioconductor-ggbio?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ggbio/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ggbio/README.html