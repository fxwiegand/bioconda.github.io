:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-listeretalbsseq'
.. highlight: bash

bioconductor-listeretalbsseq
============================

.. conda:recipe:: bioconductor-listeretalbsseq
   :replaces_section_title:
   :noindex:

   BS\-seq data of H1 and IMR90 cell line excerpted from Lister et al. 2009

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/ListerEtAlBSseq.html
   :license: Artistic 2.0
   :recipe: /`bioconductor-listeretalbsseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-listeretalbsseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-listeretalbsseq/meta.yaml>`_

   Base resolution bisulfite sequencing data of Human DNA methylomes


.. conda:package:: bioconductor-listeretalbsseq

   |downloads_bioconductor-listeretalbsseq| |docker_bioconductor-listeretalbsseq|

   :versions:
      
      

      ``1.22.0-1``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-1``,  ``1.14.0-1``,  ``1.14.0-0``

      

   
   :depends bioconductor-methylpipe: ``>=1.24.0,<1.25.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-listeretalbsseq

   and update with::

      conda update bioconductor-listeretalbsseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-listeretalbsseq:<tag>

   (see `bioconductor-listeretalbsseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-listeretalbsseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-listeretalbsseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-listeretalbsseq
   :alt:   (downloads)
.. |docker_bioconductor-listeretalbsseq| image:: https://quay.io/repository/biocontainers/bioconductor-listeretalbsseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-listeretalbsseq
.. _`bioconductor-listeretalbsseq/tags`: https://quay.io/repository/biocontainers/bioconductor-listeretalbsseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-listeretalbsseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-listeretalbsseq/README.html