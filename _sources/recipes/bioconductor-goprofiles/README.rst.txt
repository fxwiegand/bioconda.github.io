:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-goprofiles'
.. highlight: bash

bioconductor-goprofiles
=======================

.. conda:recipe:: bioconductor-goprofiles
   :replaces_section_title:
   :noindex:

   goProfiles\: an R package for the statistical analysis of functional profiles

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/goProfiles.html
   :license: GPL-2
   :recipe: /`bioconductor-goprofiles <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-goprofiles>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-goprofiles/meta.yaml>`_

   The package implements methods to compare lists of genes based on comparing the corresponding \'functional profiles\'.


.. conda:package:: bioconductor-goprofiles

   |downloads_bioconductor-goprofiles| |docker_bioconductor-goprofiles|

   :versions:
      
      

      ``1.52.0-1``,  ``1.52.0-0``,  ``1.50.0-0``,  ``1.48.0-0``,  ``1.46.0-1``,  ``1.44.0-1``,  ``1.44.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-go.db: ``>=3.12.1,<3.13.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-compquadform: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-goprofiles

   and update with::

      conda update bioconductor-goprofiles

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-goprofiles:<tag>

   (see `bioconductor-goprofiles/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-goprofiles| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-goprofiles.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-goprofiles
   :alt:   (downloads)
.. |docker_bioconductor-goprofiles| image:: https://quay.io/repository/biocontainers/bioconductor-goprofiles/status
   :target: https://quay.io/repository/biocontainers/bioconductor-goprofiles
.. _`bioconductor-goprofiles/tags`: https://quay.io/repository/biocontainers/bioconductor-goprofiles?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-goprofiles/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-goprofiles/README.html