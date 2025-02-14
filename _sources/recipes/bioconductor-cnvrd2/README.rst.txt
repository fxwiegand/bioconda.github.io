:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cnvrd2'
.. highlight: bash

bioconductor-cnvrd2
===================

.. conda:recipe:: bioconductor-cnvrd2
   :replaces_section_title:
   :noindex:

   CNVrd2\: a read depth\-based method to detect and genotype complex common copy number variants from next generation sequencing data.

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/CNVrd2.html
   :license: GPL-2
   :recipe: /`bioconductor-cnvrd2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cnvrd2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cnvrd2/meta.yaml>`_

   CNVrd2 uses next\-generation sequencing data to measure human gene copy number for multiple samples\, indentify SNPs tagging copy number variants and detect copy number polymorphic genomic regions.


.. conda:package:: bioconductor-cnvrd2

   |downloads_bioconductor-cnvrd2| |docker_bioconductor-cnvrd2|

   :versions:
      
      

      ``1.28.0-1``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.20.0-0``

      

   
   :depends bioconductor-dnacopy: ``>=1.64.0,<1.65.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-variantannotation: ``>=1.36.0,<1.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-gridextra: 
   :depends r-rjags: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cnvrd2

   and update with::

      conda update bioconductor-cnvrd2

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cnvrd2:<tag>

   (see `bioconductor-cnvrd2/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cnvrd2| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cnvrd2.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cnvrd2
   :alt:   (downloads)
.. |docker_bioconductor-cnvrd2| image:: https://quay.io/repository/biocontainers/bioconductor-cnvrd2/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cnvrd2
.. _`bioconductor-cnvrd2/tags`: https://quay.io/repository/biocontainers/bioconductor-cnvrd2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cnvrd2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cnvrd2/README.html