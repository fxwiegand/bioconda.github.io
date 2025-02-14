:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-vanillaice'
.. highlight: bash

bioconductor-vanillaice
=======================

.. conda:recipe:: bioconductor-vanillaice
   :replaces_section_title:
   :noindex:

   A Hidden Markov Model for high throughput genotyping arrays

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/VanillaICE.html
   :license: LGPL-2
   :recipe: /`bioconductor-vanillaice <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vanillaice>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-vanillaice/meta.yaml>`_
   :links: biotools: :biotools:`vanillaice`

   Hidden Markov Models for characterizing chromosomal alteration in high throughput SNP arrays.


.. conda:package:: bioconductor-vanillaice

   |downloads_bioconductor-vanillaice| |docker_bioconductor-vanillaice|

   :versions:
      
      

      ``1.52.0-2``,  ``1.52.0-1``,  ``1.52.0-0``,  ``1.50.0-0``,  ``1.48.0-0``,  ``1.46.0-1``,  ``1.44.0-0``,  ``1.42.4-0``,  ``1.40.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-bsgenome.hsapiens.ucsc.hg18: ``>=1.3.0,<1.4.0``
   :depends bioconductor-crlmm: ``>=1.48.0,<1.49.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-matrixgenerics: ``>=1.2.0,<1.3.0``
   :depends bioconductor-oligoclasses: ``>=1.52.0,<1.53.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-foreach: 
   :depends r-lattice: 
   :depends r-matrixstats: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-vanillaice

   and update with::

      conda update bioconductor-vanillaice

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-vanillaice:<tag>

   (see `bioconductor-vanillaice/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-vanillaice| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-vanillaice.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-vanillaice
   :alt:   (downloads)
.. |docker_bioconductor-vanillaice| image:: https://quay.io/repository/biocontainers/bioconductor-vanillaice/status
   :target: https://quay.io/repository/biocontainers/bioconductor-vanillaice
.. _`bioconductor-vanillaice/tags`: https://quay.io/repository/biocontainers/bioconductor-vanillaice?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-vanillaice/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-vanillaice/README.html