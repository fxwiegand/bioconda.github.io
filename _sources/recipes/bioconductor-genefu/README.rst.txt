:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-genefu'
.. highlight: bash

bioconductor-genefu
===================

.. conda:recipe:: bioconductor-genefu
   :replaces_section_title:
   :noindex:

   Computation of Gene Expression\-Based Signatures in Breast Cancer

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/genefu.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-genefu <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genefu>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genefu/meta.yaml>`_
   :links: biotools: :biotools:`genefu`, doi: :doi:`10.1093/bioinformatics/btv693`

   Description\: This package contains functions implementing various tasks usually required by gene expression analysis\, especially in breast cancer studies\: gene mapping between different microarray platforms\, identification of molecular subtypes\, implementation of published gene signatures\, gene selection\, and survival analysis.


.. conda:package:: bioconductor-genefu

   |downloads_bioconductor-genefu| |docker_bioconductor-genefu|

   :versions:
      
      

      ``2.22.1-0``,  ``2.22.0-0``,  ``2.20.0-0``,  ``2.18.0-0``,  ``2.16.0-1``,  ``2.14.0-0``,  ``2.12.0-0``,  ``2.10.0-0``

      

   
   :depends bioconductor-aims: ``>=1.22.0,<1.23.0``
   :depends bioconductor-biomart: ``>=2.46.0,<2.47.0``
   :depends bioconductor-impute: ``>=1.64.0,<1.65.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-survcomp: ``>=1.40.0,<1.41.0``
   :depends r-amap: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ic10: 
   :depends r-mclust: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-genefu

   and update with::

      conda update bioconductor-genefu

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-genefu:<tag>

   (see `bioconductor-genefu/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-genefu| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-genefu.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-genefu
   :alt:   (downloads)
.. |docker_bioconductor-genefu| image:: https://quay.io/repository/biocontainers/bioconductor-genefu/status
   :target: https://quay.io/repository/biocontainers/bioconductor-genefu
.. _`bioconductor-genefu/tags`: https://quay.io/repository/biocontainers/bioconductor-genefu?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-genefu/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-genefu/README.html