:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-basilisk.utils'
.. highlight: bash

bioconductor-basilisk.utils
===========================

.. conda:recipe:: bioconductor-basilisk.utils
   :replaces_section_title:
   :noindex:

   Basilisk Installation Utilities

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/basilisk.utils.html
   :license: GPL-3
   :recipe: /`bioconductor-basilisk.utils <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-basilisk.utils>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-basilisk.utils/meta.yaml>`_

   Implements utilities for installation of the basilisk package\, primarily for creation of the underlying Conda instance. This allows us to avoid re\-writing the same R code in both the configure script \(for centrally administered R installations\) and in the lazy installation mechanism \(for distributed package binaries\). It is highly unlikely that developers \- or\, heaven forbid\, end\-users\! \- will need to interact with this package directly\; they should be using the basilisk package instead.


.. conda:package:: bioconductor-basilisk.utils

   |downloads_bioconductor-basilisk.utils| |docker_bioconductor-basilisk.utils|

   :versions:
      
      

      ``1.2.2-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-filelock: 
   :depends r-rappdirs: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-basilisk.utils

   and update with::

      conda update bioconductor-basilisk.utils

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-basilisk.utils:<tag>

   (see `bioconductor-basilisk.utils/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-basilisk.utils| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-basilisk.utils.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-basilisk.utils
   :alt:   (downloads)
.. |docker_bioconductor-basilisk.utils| image:: https://quay.io/repository/biocontainers/bioconductor-basilisk.utils/status
   :target: https://quay.io/repository/biocontainers/bioconductor-basilisk.utils
.. _`bioconductor-basilisk.utils/tags`: https://quay.io/repository/biocontainers/bioconductor-basilisk.utils?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-basilisk.utils/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-basilisk.utils/README.html