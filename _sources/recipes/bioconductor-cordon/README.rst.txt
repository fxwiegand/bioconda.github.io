:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cordon'
.. highlight: bash

bioconductor-cordon
===================

.. conda:recipe:: bioconductor-cordon
   :replaces_section_title:
   :noindex:

   Codon Usage Analysis and Prediction of Gene Expressivity

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/coRdon.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-cordon <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cordon>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cordon/meta.yaml>`_

   Tool for analysis of codon usage in various unannotated or KEGG\/COG annotated DNA sequences. Calculates different measures of CU bias and CU\-based predictors of gene expressivity\, and performs gene set enrichment analysis for annotated sequences. Implements several methods for visualization of CU and enrichment analysis results.


.. conda:package:: bioconductor-cordon

   |downloads_bioconductor-cordon| |docker_bioconductor-cordon|

   :versions:
      
      

      ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.0.1-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-purrr: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cordon

   and update with::

      conda update bioconductor-cordon

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cordon:<tag>

   (see `bioconductor-cordon/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cordon| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cordon.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cordon
   :alt:   (downloads)
.. |docker_bioconductor-cordon| image:: https://quay.io/repository/biocontainers/bioconductor-cordon/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cordon
.. _`bioconductor-cordon/tags`: https://quay.io/repository/biocontainers/bioconductor-cordon?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cordon/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cordon/README.html