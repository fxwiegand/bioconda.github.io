:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chemminer'
.. highlight: bash

bioconductor-chemminer
======================

.. conda:recipe:: bioconductor-chemminer
   :replaces_section_title:
   :noindex:

   Cheminformatics Toolkit for R

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ChemmineR.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-chemminer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chemminer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chemminer/meta.yaml>`_
   :links: biotools: :biotools:`chemminer`

   ChemmineR is a cheminformatics package for analyzing drug\-like small molecule data in R. Its latest version contains functions for efficient processing of large numbers of molecules\, physicochemical\/structural property predictions\, structural similarity searching\, classification and clustering of compound libraries with a wide spectrum of algorithms. In addition\, it offers visualization functions for compound clustering results and chemical structures.


.. conda:package:: bioconductor-chemminer

   |downloads_bioconductor-chemminer| |docker_bioconductor-chemminer|

   :versions:
      
      

      ``3.42.2-0``,  ``3.42.0-0``,  ``3.40.0-0``,  ``3.38.0-0``,  ``3.36.0-1``,  ``3.34.1-0``,  ``3.32.1-0``,  ``2.30.0-0``,  ``2.28.3-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-base64enc: 
   :depends r-bh: 
   :depends r-dbi: 
   :depends r-digest: 
   :depends r-dt: 
   :depends r-ggplot2: 
   :depends r-gridextra: 
   :depends r-png: 
   :depends r-rcpp: ``>=0.11.0``
   :depends r-rcurl: 
   :depends r-rjson: 
   :depends r-rsvg: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chemminer

   and update with::

      conda update bioconductor-chemminer

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chemminer:<tag>

   (see `bioconductor-chemminer/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chemminer| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chemminer.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chemminer
   :alt:   (downloads)
.. |docker_bioconductor-chemminer| image:: https://quay.io/repository/biocontainers/bioconductor-chemminer/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chemminer
.. _`bioconductor-chemminer/tags`: https://quay.io/repository/biocontainers/bioconductor-chemminer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chemminer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chemminer/README.html