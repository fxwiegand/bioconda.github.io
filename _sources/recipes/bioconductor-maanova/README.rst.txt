:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-maanova'
.. highlight: bash

bioconductor-maanova
====================

.. conda:recipe:: bioconductor-maanova
   :replaces_section_title:
   :noindex:

   Tools for analyzing Micro Array experiments

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/maanova.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-maanova <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-maanova>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-maanova/meta.yaml>`_
   :links: biotools: :biotools:`maanova`, doi: :doi:`10.1007/0-387-21679-0_14`

   Analysis of N\-dye Micro Array experiment using mixed model effect. Containing analysis of variance\, permutation and bootstrap\, cluster and consensus tree.


.. conda:package:: bioconductor-maanova

   |downloads_bioconductor-maanova| |docker_bioconductor-maanova|

   :versions:
      
      

      ``1.60.0-1``,  ``1.60.0-0``,  ``1.58.0-0``,  ``1.56.0-0``,  ``1.54.0-1``,  ``1.52.0-0``,  ``1.50.0-0``,  ``1.48.0-0``,  ``1.46.1-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-maanova

   and update with::

      conda update bioconductor-maanova

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-maanova:<tag>

   (see `bioconductor-maanova/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-maanova| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-maanova.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-maanova
   :alt:   (downloads)
.. |docker_bioconductor-maanova| image:: https://quay.io/repository/biocontainers/bioconductor-maanova/status
   :target: https://quay.io/repository/biocontainers/bioconductor-maanova
.. _`bioconductor-maanova/tags`: https://quay.io/repository/biocontainers/bioconductor-maanova?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-maanova/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-maanova/README.html