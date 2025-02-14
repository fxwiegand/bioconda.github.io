:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pqsfinder'
.. highlight: bash

bioconductor-pqsfinder
======================

.. conda:recipe:: bioconductor-pqsfinder
   :replaces_section_title:
   :noindex:

   Identification of potential quadruplex forming sequences

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/pqsfinder.html
   :license: BSD_2_clause + file LICENSE
   :recipe: /`bioconductor-pqsfinder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pqsfinder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pqsfinder/meta.yaml>`_
   :links: biotools: :biotools:`pqsfinder`, doi: :doi:`10.1093/bioinformatics/btv272`

   Pqsfinder detects DNA and RNA sequence patterns that are likely to fold into an intramolecular G\-quadruplex \(G4\). Unlike many other approaches\, pqsfinder is able to detect G4s folded from imperfect G\-runs containing bulges or mismatches or G4s having long loops. Pqsfinder also assigns an integer score to each hit that was fitted on G4 sequencing data and corresponds to expected stability of the folded G4.


.. conda:package:: bioconductor-pqsfinder

   |downloads_bioconductor-pqsfinder| |docker_bioconductor-pqsfinder|

   :versions:
      
      

      ``2.6.0-1``,  ``2.6.0-0``,  ``2.4.0-0``,  ``2.2.0-0``,  ``2.0.1-0``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.3-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-bh: ``>=1.69.0``
   :depends r-rcpp: ``>=0.12.3``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pqsfinder

   and update with::

      conda update bioconductor-pqsfinder

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pqsfinder:<tag>

   (see `bioconductor-pqsfinder/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pqsfinder| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pqsfinder.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pqsfinder
   :alt:   (downloads)
.. |docker_bioconductor-pqsfinder| image:: https://quay.io/repository/biocontainers/bioconductor-pqsfinder/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pqsfinder
.. _`bioconductor-pqsfinder/tags`: https://quay.io/repository/biocontainers/bioconductor-pqsfinder?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pqsfinder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pqsfinder/README.html