:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-grohmm'
.. highlight: bash

bioconductor-grohmm
===================

.. conda:recipe:: bioconductor-grohmm
   :replaces_section_title:
   :noindex:

   GRO\-seq Analysis Pipeline

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/groHMM.html
   :license: GPL-3
   :recipe: /`bioconductor-grohmm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-grohmm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-grohmm/meta.yaml>`_

   A pipeline for the analysis of GRO\-seq data.


.. conda:package:: bioconductor-grohmm

   |downloads_bioconductor-grohmm| |docker_bioconductor-grohmm|

   :versions:
      
      

      ``1.24.0-1``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.16.0-0``

      

   
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-mass: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-grohmm

   and update with::

      conda update bioconductor-grohmm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-grohmm:<tag>

   (see `bioconductor-grohmm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-grohmm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-grohmm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-grohmm
   :alt:   (downloads)
.. |docker_bioconductor-grohmm| image:: https://quay.io/repository/biocontainers/bioconductor-grohmm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-grohmm
.. _`bioconductor-grohmm/tags`: https://quay.io/repository/biocontainers/bioconductor-grohmm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-grohmm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-grohmm/README.html