:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-multidataset'
.. highlight: bash

bioconductor-multidataset
=========================

.. conda:recipe:: bioconductor-multidataset
   :replaces_section_title:
   :noindex:

   Implementation of MultiDataSet and ResultSet

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/MultiDataSet.html
   :license: file LICENSE
   :recipe: /`bioconductor-multidataset <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-multidataset>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-multidataset/meta.yaml>`_
   :links: biotools: :biotools:`multidataset`

   Implementation of the BRGE\'s \(Bioinformatic Research Group in Epidemiology from Center for Research in Environmental Epidemiology\) MultiDataSet and ResultSet. MultiDataSet is designed for integrating multi omics data sets and ResultSet is a container for omics results. This package contains base classes for MEAL and rexposome packages.


.. conda:package:: bioconductor-multidataset

   |downloads_bioconductor-multidataset| |docker_bioconductor-multidataset|

   :versions:
      
      

      ``1.18.1-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-qqman: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-multidataset

   and update with::

      conda update bioconductor-multidataset

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-multidataset:<tag>

   (see `bioconductor-multidataset/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-multidataset| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-multidataset.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-multidataset
   :alt:   (downloads)
.. |docker_bioconductor-multidataset| image:: https://quay.io/repository/biocontainers/bioconductor-multidataset/status
   :target: https://quay.io/repository/biocontainers/bioconductor-multidataset
.. _`bioconductor-multidataset/tags`: https://quay.io/repository/biocontainers/bioconductor-multidataset?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-multidataset/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-multidataset/README.html