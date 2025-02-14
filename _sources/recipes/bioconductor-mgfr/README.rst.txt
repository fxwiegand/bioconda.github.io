:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mgfr'
.. highlight: bash

bioconductor-mgfr
=================

.. conda:recipe:: bioconductor-mgfr
   :replaces_section_title:
   :noindex:

   Marker Gene Finder in RNA\-seq data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/MGFR.html
   :license: GPL-3
   :recipe: /`bioconductor-mgfr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mgfr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mgfr/meta.yaml>`_
   :links: biotools: :biotools:`mgfr`, doi: :doi:`10.1186/s12864-015-1785-9`

   The package is designed to detect marker genes from RNA\-seq data.


.. conda:package:: bioconductor-mgfr

   |downloads_bioconductor-mgfr| |docker_bioconductor-mgfr|

   :versions:
      
      

      ``1.16.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``

      

   
   :depends bioconductor-annotate: ``>=1.68.0,<1.69.0``
   :depends bioconductor-biomart: ``>=2.46.0,<2.47.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mgfr

   and update with::

      conda update bioconductor-mgfr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mgfr:<tag>

   (see `bioconductor-mgfr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mgfr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mgfr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mgfr
   :alt:   (downloads)
.. |docker_bioconductor-mgfr| image:: https://quay.io/repository/biocontainers/bioconductor-mgfr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mgfr
.. _`bioconductor-mgfr/tags`: https://quay.io/repository/biocontainers/bioconductor-mgfr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mgfr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mgfr/README.html