:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ribosomeprofilingqc'
.. highlight: bash

bioconductor-ribosomeprofilingqc
================================

.. conda:recipe:: bioconductor-ribosomeprofilingqc
   :replaces_section_title:
   :noindex:

   Ribosome Profiling Quality Control

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ribosomeProfilingQC.html
   :license: GPL (>=3) + file LICENSE
   :recipe: /`bioconductor-ribosomeprofilingqc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ribosomeprofilingqc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ribosomeprofilingqc/meta.yaml>`_

   Ribo\-Seq \(also named ribosome profiling or footprinting\) measures translatome \(unlike RNA\-Seq\, which sequences the transcriptome\) by direct quantification of the ribosome\-protected fragments \(RPFs\). This package provides the tools for quality assessment of ribosome profiling. In addition\, it can preprocess Ribo\-Seq data for subsequent differential analysis.


.. conda:package:: bioconductor-ribosomeprofilingqc

   |downloads_bioconductor-ribosomeprofilingqc| |docker_bioconductor-ribosomeprofilingqc|

   :versions:
      
      

      ``1.2.1-0``,  ``1.2.0-0``,  ``1.0.1-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-bsgenome: ``>=1.58.0,<1.59.0``
   :depends bioconductor-edaseq: ``>=2.24.0,<2.25.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-motifstack: ``>=1.34.0,<1.35.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-rsubread: ``>=2.4.0,<2.5.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-ruvseq: ``>=1.24.0,<1.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-xvector: ``>=0.30.0,<0.31.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cluster: 
   :depends r-ggfittext: 
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-scales: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ribosomeprofilingqc

   and update with::

      conda update bioconductor-ribosomeprofilingqc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ribosomeprofilingqc:<tag>

   (see `bioconductor-ribosomeprofilingqc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ribosomeprofilingqc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ribosomeprofilingqc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ribosomeprofilingqc
   :alt:   (downloads)
.. |docker_bioconductor-ribosomeprofilingqc| image:: https://quay.io/repository/biocontainers/bioconductor-ribosomeprofilingqc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ribosomeprofilingqc
.. _`bioconductor-ribosomeprofilingqc/tags`: https://quay.io/repository/biocontainers/bioconductor-ribosomeprofilingqc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ribosomeprofilingqc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ribosomeprofilingqc/README.html