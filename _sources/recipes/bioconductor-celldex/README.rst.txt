:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-celldex'
.. highlight: bash

bioconductor-celldex
====================

.. conda:recipe:: bioconductor-celldex
   :replaces_section_title:
   :noindex:

   Reference Index for Cell Types

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/celldex.html
   :license: GPL-3
   :recipe: /`bioconductor-celldex <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-celldex>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-celldex/meta.yaml>`_

   Provides a collection of reference expression datasets with curated cell type labels\, for use in procedures like automated annotation of single\-cell data or deconvolution of bulk RNA\-seq.


.. conda:package:: bioconductor-celldex

   |downloads_bioconductor-celldex| |docker_bioconductor-celldex|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-annotationhub: ``>=2.22.0,<2.23.0``
   :depends bioconductor-delayedarray: ``>=0.16.0,<0.17.0``
   :depends bioconductor-delayedmatrixstats: ``>=1.12.0,<1.13.0``
   :depends bioconductor-experimenthub: ``>=1.16.0,<1.17.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-celldex

   and update with::

      conda update bioconductor-celldex

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-celldex:<tag>

   (see `bioconductor-celldex/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-celldex| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-celldex.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-celldex
   :alt:   (downloads)
.. |docker_bioconductor-celldex| image:: https://quay.io/repository/biocontainers/bioconductor-celldex/status
   :target: https://quay.io/repository/biocontainers/bioconductor-celldex
.. _`bioconductor-celldex/tags`: https://quay.io/repository/biocontainers/bioconductor-celldex?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-celldex/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-celldex/README.html