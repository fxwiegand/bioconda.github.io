:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cohcap'
.. highlight: bash

bioconductor-cohcap
===================

.. conda:recipe:: bioconductor-cohcap
   :replaces_section_title:
   :noindex:

   CpG Island Analysis Pipeline for Illumina Methylation Array and Targeted BS\-Seq Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/COHCAP.html
   :license: GPL-3
   :recipe: /`bioconductor-cohcap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cohcap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cohcap/meta.yaml>`_
   :links: biotools: :biotools:`cohcap`

   COHCAP \(pronounced \"co\-cap\"\) provides a pipeline to analyze single\-nucleotide resolution methylation data \(Illumina 450k\/EPIC methylation array\, targeted BS\-Seq\, etc.\). It provides differential methylation for CpG Sites\, differential methylation for CpG Islands\, integration with gene expression data\, with visualizaton options. Discussion Group\: https\:\/\/sourceforge.net\/p\/cohcap\/discussion\/bioconductor\/


.. conda:package:: bioconductor-cohcap

   |downloads_bioconductor-cohcap| |docker_bioconductor-cohcap|

   :versions:
      
      

      ``1.36.0-1``,  ``1.36.0-0``,  ``1.34.1-0``,  ``1.32.0-1``,  ``1.30.0-1``,  ``1.30.0-0``,  ``1.28.1-0``,  ``1.26.0-0``,  ``1.24.0-0``

      

   
   :depends bioconductor-cohcapanno: ``>=1.26.0,<1.27.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends perl: ``>=5.26.2,<5.26.3.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-bh: 
   :depends r-gplots: 
   :depends r-rcolorbrewer: 
   :depends r-rcpp: 
   :depends r-rcpparmadillo: 
   :depends r-writexls: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cohcap

   and update with::

      conda update bioconductor-cohcap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cohcap:<tag>

   (see `bioconductor-cohcap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cohcap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cohcap.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cohcap
   :alt:   (downloads)
.. |docker_bioconductor-cohcap| image:: https://quay.io/repository/biocontainers/bioconductor-cohcap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cohcap
.. _`bioconductor-cohcap/tags`: https://quay.io/repository/biocontainers/bioconductor-cohcap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cohcap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cohcap/README.html