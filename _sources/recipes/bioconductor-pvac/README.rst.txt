:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pvac'
.. highlight: bash

bioconductor-pvac
=================

.. conda:recipe:: bioconductor-pvac
   :replaces_section_title:
   :noindex:

   PCA\-based gene filtering for Affymetrix arrays

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/pvac.html
   :license: LGPL (>= 2.0)
   :recipe: /`bioconductor-pvac <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pvac>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pvac/meta.yaml>`_
   :links: biotools: :biotools:`pvac`, doi: :doi:`10.1093/nar/gkr241`

   The package contains the function for filtering genes by the proportion of variation accounted for by the first principal component \(PVAC\).


.. conda:package:: bioconductor-pvac

   |downloads_bioconductor-pvac| |docker_bioconductor-pvac|

   :versions:
      
      

      ``1.38.0-1``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-1``,  ``1.30.0-0``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``

      

   
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pvac

   and update with::

      conda update bioconductor-pvac

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pvac:<tag>

   (see `bioconductor-pvac/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pvac| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pvac.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pvac
   :alt:   (downloads)
.. |docker_bioconductor-pvac| image:: https://quay.io/repository/biocontainers/bioconductor-pvac/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pvac
.. _`bioconductor-pvac/tags`: https://quay.io/repository/biocontainers/bioconductor-pvac?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pvac/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pvac/README.html