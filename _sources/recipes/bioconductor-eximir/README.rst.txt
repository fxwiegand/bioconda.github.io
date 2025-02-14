:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-eximir'
.. highlight: bash

bioconductor-eximir
===================

.. conda:recipe:: bioconductor-eximir
   :replaces_section_title:
   :noindex:

   R functions for the normalization of Exiqon miRNA array data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ExiMiR.html
   :license: GPL-2
   :recipe: /`bioconductor-eximir <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-eximir>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-eximir/meta.yaml>`_
   :links: biotools: :biotools:`eximir`, doi: :doi:`10.1186/1756-0500-7-302`

   This package contains functions for reading raw data in ImaGene TXT format obtained from Exiqon miRCURY LNA arrays\, annotating them with appropriate GAL files\, and normalizing them using a spike\-in probe\-based method. Other platforms and data formats are also supported.


.. conda:package:: bioconductor-eximir

   |downloads_bioconductor-eximir| |docker_bioconductor-eximir|

   :versions:
      
      

      ``2.32.0-1``,  ``2.32.0-0``,  ``2.30.0-0``,  ``2.28.0-0``,  ``2.26.0-1``,  ``2.24.0-0``,  ``2.22.0-0``,  ``2.20.0-0``

      

   
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends bioconductor-affyio: ``>=1.60.0,<1.61.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-preprocesscore: ``>=1.52.0,<1.53.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-eximir

   and update with::

      conda update bioconductor-eximir

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-eximir:<tag>

   (see `bioconductor-eximir/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-eximir| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-eximir.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-eximir
   :alt:   (downloads)
.. |docker_bioconductor-eximir| image:: https://quay.io/repository/biocontainers/bioconductor-eximir/status
   :target: https://quay.io/repository/biocontainers/bioconductor-eximir
.. _`bioconductor-eximir/tags`: https://quay.io/repository/biocontainers/bioconductor-eximir?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-eximir/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-eximir/README.html