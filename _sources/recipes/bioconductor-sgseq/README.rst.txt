:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-sgseq'
.. highlight: bash

bioconductor-sgseq
==================

.. conda:recipe:: bioconductor-sgseq
   :replaces_section_title:
   :noindex:

   Splice event prediction and quantification from RNA\-seq data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/SGSeq.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-sgseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sgseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sgseq/meta.yaml>`_
   :links: biotools: :biotools:`sgseq`

   SGSeq is a software package for analyzing splice events from RNA\-seq data. Input data are RNA\-seq reads mapped to a reference genome in BAM format. Genes are represented as a splice graph\, which can be obtained from existing annotation or predicted from the mapped sequence reads. Splice events are identified from the graph and are quantified locally using structurally compatible reads at the start or end of each splice variant. The software includes functions for splice event prediction\, quantification\, visualization and interpretation.


.. conda:package:: bioconductor-sgseq

   |downloads_bioconductor-sgseq| |docker_bioconductor-sgseq|

   :versions:
      
      

      ``1.24.0-1``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.16.2-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-igraph: 
   :depends r-runit: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-sgseq

   and update with::

      conda update bioconductor-sgseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-sgseq:<tag>

   (see `bioconductor-sgseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-sgseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-sgseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-sgseq
   :alt:   (downloads)
.. |docker_bioconductor-sgseq| image:: https://quay.io/repository/biocontainers/bioconductor-sgseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-sgseq
.. _`bioconductor-sgseq/tags`: https://quay.io/repository/biocontainers/bioconductor-sgseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-sgseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-sgseq/README.html