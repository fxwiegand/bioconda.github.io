:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chic'
.. highlight: bash

bioconductor-chic
=================

.. conda:recipe:: bioconductor-chic
   :replaces_section_title:
   :noindex:

   Quality Control Pipeline for ChIP\-Seq Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ChIC.html
   :license: GPL-2
   :recipe: /`bioconductor-chic <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chic>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chic/meta.yaml>`_

   Quality control \(QC\) pipeline for ChIP\-seq data using a comprehensive set of QC metrics\, including previously proposed metrics as well as novel ones\, based on local characteristics of the enrichment profile. The package provides functions to calculate a set of QC metrics\, a compendium with reference values and machine learning models to score sample quality.


.. conda:package:: bioconductor-chic

   |downloads_bioconductor-chic| |docker_bioconductor-chic|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-1``,  ``1.4.0-1``,  ``1.2.0-1``,  ``1.2.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-chic.data: ``>=1.10.0,<1.11.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-caret: 
   :depends r-catools: 
   :depends r-progress: 
   :depends r-spp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chic

   and update with::

      conda update bioconductor-chic

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chic:<tag>

   (see `bioconductor-chic/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chic| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chic.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chic
   :alt:   (downloads)
.. |docker_bioconductor-chic| image:: https://quay.io/repository/biocontainers/bioconductor-chic/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chic
.. _`bioconductor-chic/tags`: https://quay.io/repository/biocontainers/bioconductor-chic?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chic/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chic/README.html