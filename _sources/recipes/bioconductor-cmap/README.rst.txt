:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cmap'
.. highlight: bash

bioconductor-cmap
=================

.. conda:recipe:: bioconductor-cmap
   :replaces_section_title:
   :noindex:

   A data package containing annotation data for cMAP

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/cMAP.html
   :license: LGPL
   :recipe: /`bioconductor-cmap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cmap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cmap/meta.yaml>`_

   Annotation data file for cMAP assembled using data from public data repositories


.. conda:package:: bioconductor-cmap

   |downloads_bioconductor-cmap| |docker_bioconductor-cmap|

   :versions:
      
      

      ``1.15.1-9``,  ``1.15.1-8``,  ``1.15.1-7``,  ``1.15.1-6``,  ``1.15.1-5``,  ``1.15.1-4``,  ``1.15.1-3``,  ``1.15.1-2``,  ``1.15.1-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cmap

   and update with::

      conda update bioconductor-cmap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cmap:<tag>

   (see `bioconductor-cmap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cmap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cmap.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cmap
   :alt:   (downloads)
.. |docker_bioconductor-cmap| image:: https://quay.io/repository/biocontainers/bioconductor-cmap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cmap
.. _`bioconductor-cmap/tags`: https://quay.io/repository/biocontainers/bioconductor-cmap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cmap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cmap/README.html