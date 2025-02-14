:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-genomicfiles'
.. highlight: bash

bioconductor-genomicfiles
=========================

.. conda:recipe:: bioconductor-genomicfiles
   :replaces_section_title:
   :noindex:

   Distributed computing by file or by range

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/GenomicFiles.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-genomicfiles <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomicfiles>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomicfiles/meta.yaml>`_
   :links: biotools: :biotools:`genomicfiles`, doi: :doi:`10.1038/nmeth.3252`

   This package provides infrastructure for parallel computations distributed \'by file\' or \'by range\'. User defined MAPPER and REDUCER functions provide added flexibility for data combination and manipulation.


.. conda:package:: bioconductor-genomicfiles

   |downloads_bioconductor-genomicfiles| |docker_bioconductor-genomicfiles|

   :versions:
      
      

      ``1.26.0-1``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-1``,  ``1.18.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-matrixgenerics: ``>=1.2.0,<1.3.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends bioconductor-variantannotation: ``>=1.36.0,<1.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-genomicfiles

   and update with::

      conda update bioconductor-genomicfiles

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-genomicfiles:<tag>

   (see `bioconductor-genomicfiles/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-genomicfiles| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-genomicfiles.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-genomicfiles
   :alt:   (downloads)
.. |docker_bioconductor-genomicfiles| image:: https://quay.io/repository/biocontainers/bioconductor-genomicfiles/status
   :target: https://quay.io/repository/biocontainers/bioconductor-genomicfiles
.. _`bioconductor-genomicfiles/tags`: https://quay.io/repository/biocontainers/bioconductor-genomicfiles?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-genomicfiles/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-genomicfiles/README.html