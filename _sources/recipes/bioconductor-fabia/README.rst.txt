:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fabia'
.. highlight: bash

bioconductor-fabia
==================

.. conda:recipe:: bioconductor-fabia
   :replaces_section_title:
   :noindex:

   FABIA\: Factor Analysis for Bicluster Acquisition

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/fabia.html
   :license: LGPL (>= 2.1)
   :recipe: /`bioconductor-fabia <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fabia>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fabia/meta.yaml>`_
   :links: biotools: :biotools:`fabia`

   Biclustering by \"Factor Analysis for Bicluster Acquisition\" \(FABIA\). FABIA is a model\-based technique for biclustering\, that is clustering rows and columns simultaneously. Biclusters are found by factor analysis where both the factors and the loading matrix are sparse. FABIA is a multiplicative model that extracts linear dependencies between samples and feature patterns. It captures realistic non\-Gaussian data distributions with heavy tails as observed in gene expression measurements. FABIA utilizes well understood model selection techniques like the EM algorithm and variational approaches and is embedded into a Bayesian framework. FABIA ranks biclusters according to their information content and separates spurious biclusters from true biclusters. The code is written in C.


.. conda:package:: bioconductor-fabia

   |downloads_bioconductor-fabia| |docker_bioconductor-fabia|

   :versions:
      
      

      ``2.36.0-1``,  ``2.36.0-0``,  ``2.34.0-0``,  ``2.32.0-0``,  ``2.30.0-1``,  ``2.28.0-0``,  ``2.26.0-0``,  ``2.24.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-fabia

   and update with::

      conda update bioconductor-fabia

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fabia:<tag>

   (see `bioconductor-fabia/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fabia| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fabia.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fabia
   :alt:   (downloads)
.. |docker_bioconductor-fabia| image:: https://quay.io/repository/biocontainers/bioconductor-fabia/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fabia
.. _`bioconductor-fabia/tags`: https://quay.io/repository/biocontainers/bioconductor-fabia?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fabia/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fabia/README.html