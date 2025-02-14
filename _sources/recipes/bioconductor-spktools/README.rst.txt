:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-spktools'
.. highlight: bash

bioconductor-spktools
=====================

.. conda:recipe:: bioconductor-spktools
   :replaces_section_title:
   :noindex:

   Methods for Spike\-in Arrays

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/spkTools.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-spktools <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spktools>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spktools/meta.yaml>`_
   :links: biotools: :biotools:`spktools`, doi: :doi:`10.1093/nar/gkn430`

   The package contains functions that can be used to compare expression measures on different array platforms.


.. conda:package:: bioconductor-spktools

   |downloads_bioconductor-spktools| |docker_bioconductor-spktools|

   :versions:
      
      

      ``1.46.0-1``,  ``1.46.0-0``,  ``1.44.0-0``,  ``1.42.0-0``,  ``1.40.0-1``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-gtools: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-spktools

   and update with::

      conda update bioconductor-spktools

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-spktools:<tag>

   (see `bioconductor-spktools/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-spktools| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-spktools.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-spktools
   :alt:   (downloads)
.. |docker_bioconductor-spktools| image:: https://quay.io/repository/biocontainers/bioconductor-spktools/status
   :target: https://quay.io/repository/biocontainers/bioconductor-spktools
.. _`bioconductor-spktools/tags`: https://quay.io/repository/biocontainers/bioconductor-spktools?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-spktools/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-spktools/README.html