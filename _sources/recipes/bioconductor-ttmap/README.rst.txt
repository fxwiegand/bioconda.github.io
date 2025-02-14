:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-ttmap'
.. highlight: bash

bioconductor-ttmap
==================

.. conda:recipe:: bioconductor-ttmap
   :replaces_section_title:
   :noindex:

   Two\-Tier Mapper\: a clustering tool based on topological data analysis

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/TTMap.html
   :license: GPL-2
   :recipe: /`bioconductor-ttmap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ttmap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-ttmap/meta.yaml>`_

   TTMap is a clustering method that groups together samples with the same deviation in comparison to a control group. It is specially useful when the data is small. It is parameter free.


.. conda:package:: bioconductor-ttmap

   |downloads_bioconductor-ttmap| |docker_bioconductor-ttmap|

   :versions:
      
      

      ``1.12.0-1``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-1``,  ``1.4.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-colorramps: 
   :depends r-rgl: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-ttmap

   and update with::

      conda update bioconductor-ttmap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-ttmap:<tag>

   (see `bioconductor-ttmap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-ttmap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-ttmap.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-ttmap
   :alt:   (downloads)
.. |docker_bioconductor-ttmap| image:: https://quay.io/repository/biocontainers/bioconductor-ttmap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-ttmap
.. _`bioconductor-ttmap/tags`: https://quay.io/repository/biocontainers/bioconductor-ttmap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-ttmap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-ttmap/README.html