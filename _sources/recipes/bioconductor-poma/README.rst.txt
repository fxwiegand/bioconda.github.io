:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-poma'
.. highlight: bash

bioconductor-poma
=================

.. conda:recipe:: bioconductor-poma
   :replaces_section_title:
   :noindex:

   User\-friendly Workflow for Pre\-processing and Statistical Analysis of Mass Spectrometry Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/POMA.html
   :license: GPL-3
   :recipe: /`bioconductor-poma <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-poma>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-poma/meta.yaml>`_

   POMA introduces a structured\, reproducible and easy\-to\-use workflow for the visualization\, pre\-processing\, exploratory and statistical analysis of mass spectrometry data. The main aim of POMA is to enable a flexible data cleaning and statistical analysis processes in one comprehensible and user\-friendly R package. This package also has a Shiny app version that implements all POMA functions. See https\:\/\/github.com\/pcastellanoescuder\/POMAShiny.


.. conda:package:: bioconductor-poma

   |downloads_bioconductor-poma| |docker_bioconductor-poma|

   :versions:
      
      

      ``1.0.0-2``,  ``1.0.0-1``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-complexheatmap: ``>=2.6.0,<2.7.0``
   :depends bioconductor-impute: ``>=1.64.0,<1.65.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-mixomics: ``>=6.14.0,<6.15.0``
   :depends bioconductor-msnbase: ``>=2.16.0,<2.17.0``
   :depends bioconductor-rankprod: ``>=3.16.0,<3.17.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-broom: 
   :depends r-caret: 
   :depends r-clisymbols: 
   :depends r-crayon: 
   :depends r-dplyr: 
   :depends r-e1071: 
   :depends r-ggcorrplot: 
   :depends r-ggplot2: 
   :depends r-ggraph: 
   :depends r-ggrepel: 
   :depends r-glasso: ``>=1.11``
   :depends r-glmnet: 
   :depends r-knitr: 
   :depends r-magrittr: 
   :depends r-patchwork: 
   :depends r-plotly: 
   :depends r-qpdf: 
   :depends r-randomforest: 
   :depends r-reshape2: 
   :depends r-rmarkdown: 
   :depends r-tibble: 
   :depends r-tidyr: 
   :depends r-vegan: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-poma

   and update with::

      conda update bioconductor-poma

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-poma:<tag>

   (see `bioconductor-poma/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-poma| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-poma.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-poma
   :alt:   (downloads)
.. |docker_bioconductor-poma| image:: https://quay.io/repository/biocontainers/bioconductor-poma/status
   :target: https://quay.io/repository/biocontainers/bioconductor-poma
.. _`bioconductor-poma/tags`: https://quay.io/repository/biocontainers/bioconductor-poma?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-poma/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-poma/README.html