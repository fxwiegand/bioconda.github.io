:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-a4preproc'
.. highlight: bash

bioconductor-a4preproc
======================

.. conda:recipe:: bioconductor-a4preproc
   :replaces_section_title:
   :noindex:

   Automated Affymetrix Array Analysis Preprocessing Package

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/a4Preproc.html
   :license: GPL-3
   :recipe: /`bioconductor-a4preproc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-a4preproc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-a4preproc/meta.yaml>`_
   :links: biotools: :biotools:`a4preproc`, doi: :doi:`10.1038/nmeth.3252`

   Utility functions to pre\-process data for the Automated Affymetrix Array Analysis set of packages.


.. conda:package:: bioconductor-a4preproc

   |downloads_bioconductor-a4preproc| |docker_bioconductor-a4preproc|

   :versions:
      
      

      ``1.38.0-1``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-1``,  ``1.30.0-0``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-a4preproc

   and update with::

      conda update bioconductor-a4preproc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-a4preproc:<tag>

   (see `bioconductor-a4preproc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-a4preproc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-a4preproc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-a4preproc
   :alt:   (downloads)
.. |docker_bioconductor-a4preproc| image:: https://quay.io/repository/biocontainers/bioconductor-a4preproc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-a4preproc
.. _`bioconductor-a4preproc/tags`: https://quay.io/repository/biocontainers/bioconductor-a4preproc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-a4preproc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-a4preproc/README.html