:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-a4base'
.. highlight: bash

bioconductor-a4base
===================

.. conda:recipe:: bioconductor-a4base
   :replaces_section_title:
   :noindex:

   Automated Affymetrix Array Analysis Base Package

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/a4Base.html
   :license: GPL-3
   :recipe: /`bioconductor-a4base <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-a4base>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-a4base/meta.yaml>`_
   :links: biotools: :biotools:`a4base`, doi: :doi:`10.1038/nmeth.3252`

   Base utility functions are available for the Automated Affymetrix Array Analysis set of packages.


.. conda:package:: bioconductor-a4base

   |downloads_bioconductor-a4base| |docker_bioconductor-a4base|

   :versions:
      
      

      ``1.38.0-1``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-1``,  ``1.30.0-0``,  ``1.28.0-0``,  ``1.26.0-0``

      

   
   :depends bioconductor-a4core: ``>=1.38.0,<1.39.0``
   :depends bioconductor-a4preproc: ``>=1.38.0,<1.39.0``
   :depends bioconductor-annaffy: ``>=1.62.0,<1.63.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-genefilter: ``>=1.72.0,<1.73.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-multtest: ``>=2.46.0,<2.47.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-glmnet: 
   :depends r-gplots: 
   :depends r-mpm: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-a4base

   and update with::

      conda update bioconductor-a4base

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-a4base:<tag>

   (see `bioconductor-a4base/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-a4base| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-a4base.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-a4base
   :alt:   (downloads)
.. |docker_bioconductor-a4base| image:: https://quay.io/repository/biocontainers/bioconductor-a4base/status
   :target: https://quay.io/repository/biocontainers/bioconductor-a4base
.. _`bioconductor-a4base/tags`: https://quay.io/repository/biocontainers/bioconductor-a4base?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-a4base/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-a4base/README.html