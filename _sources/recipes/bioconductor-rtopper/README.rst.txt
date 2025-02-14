:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rtopper'
.. highlight: bash

bioconductor-rtopper
====================

.. conda:recipe:: bioconductor-rtopper
   :replaces_section_title:
   :noindex:

   This package is designed to perform Gene Set Analysis across multiple genomic platforms

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/RTopper.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-rtopper <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rtopper>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rtopper/meta.yaml>`_
   :links: biotools: :biotools:`rtopper`

   the RTopper package is designed to perform and integrate gene set enrichment results across multiple genomic platforms.


.. conda:package:: bioconductor-rtopper

   |downloads_bioconductor-rtopper| |docker_bioconductor-rtopper|

   :versions:
      
      

      ``1.36.0-1``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``,  ``1.30.0-1``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-multtest: ``>=2.46.0,<2.47.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rtopper

   and update with::

      conda update bioconductor-rtopper

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rtopper:<tag>

   (see `bioconductor-rtopper/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rtopper| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rtopper.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rtopper
   :alt:   (downloads)
.. |docker_bioconductor-rtopper| image:: https://quay.io/repository/biocontainers/bioconductor-rtopper/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rtopper
.. _`bioconductor-rtopper/tags`: https://quay.io/repository/biocontainers/bioconductor-rtopper?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rtopper/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rtopper/README.html