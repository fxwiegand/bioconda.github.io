:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-biomartr'
.. highlight: bash

r-biomartr
==========

.. conda:recipe:: r-biomartr
   :replaces_section_title:
   :noindex:

   Perform large scale genomic data retrieval and functional annotation retrieval. This package aims to provide users with a standardized way to automate genome\, proteome\, \'RNA\'\, coding sequence \(\'CDS\'\)\, \'GFF\'\, and metagenome retrieval from \'NCBI RefSeq\'\, \'NCBI Genbank\'\, \'ENSEMBL\'\, \'ENSEMBLGENOMES\'\, and \'UniProt\' databases. Furthermore\, an interface to the \'BioMart\' database \(Smedley et al. \(2009\) \<doi\:10.1186\/1471\-2164\-10\-22\>\) allows users to retrieve functional annotation for genomic loci. In addition\, users can download entire databases such as \'NCBI RefSeq\' \(Pruitt et al. \(2007\) \<doi\:10.1093\/nar\/gkl842\>\)\, \'NCBI nr\'\, \'NCBI nt\'\, \'NCBI Genbank\' \(Benson et al. \(2013\) \<doi\:10.1093\/nar\/gks1195\>\)\, etc. as well as \'ENSEMBL\' and \'ENSEMBLGENOMES\' with only one command.

   :homepage: https://docs.ropensci.org/biomartr, https://github.com/ropensci/biomartr
   :license: GPL2 / GPL-2
   :recipe: /`r-biomartr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-biomartr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-biomartr/meta.yaml>`_

   


.. conda:package:: r-biomartr

   |downloads_r-biomartr| |docker_r-biomartr|

   :versions:
      
      

      ``0.9.2-1``,  ``0.9.2-0``

      

   
   :depends bioconductor-biomart: 
   :depends bioconductor-biostrings: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-curl: 
   :depends r-data.table: ``>=1.9.4``
   :depends r-downloader: ``>=0.3``
   :depends r-dplyr: ``>=0.3.0``
   :depends r-fs: ``>=1.3.1``
   :depends r-httr: ``>=0.6.1``
   :depends r-jsonlite: 
   :depends r-philentropy: 
   :depends r-purrr: 
   :depends r-r.utils: 
   :depends r-rcurl: ``>=1.95_4.5``
   :depends r-readr: ``>=0.2.2``
   :depends r-stringr: ``>=0.6.2``
   :depends r-tibble: 
   :depends r-xml: ``>=3.98_1.1``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-biomartr

   and update with::

      conda update r-biomartr

   or use the docker container::

      docker pull quay.io/biocontainers/r-biomartr:<tag>

   (see `r-biomartr/tags`_ for valid values for ``<tag>``)


.. |downloads_r-biomartr| image:: https://img.shields.io/conda/dn/bioconda/r-biomartr.svg?style=flat
   :target: https://anaconda.org/bioconda/r-biomartr
   :alt:   (downloads)
.. |docker_r-biomartr| image:: https://quay.io/repository/biocontainers/r-biomartr/status
   :target: https://quay.io/repository/biocontainers/r-biomartr
.. _`r-biomartr/tags`: https://quay.io/repository/biocontainers/r-biomartr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-biomartr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-biomartr/README.html