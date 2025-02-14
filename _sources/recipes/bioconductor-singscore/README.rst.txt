:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-singscore'
.. highlight: bash

bioconductor-singscore
======================

.. conda:recipe:: bioconductor-singscore
   :replaces_section_title:
   :noindex:

   Rank\-based single\-sample gene set scoring method

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/singscore.html
   :license: GPL-3
   :recipe: /`bioconductor-singscore <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-singscore>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-singscore/meta.yaml>`_

   A simple single\-sample gene signature scoring method that uses rank\-based statistics to analyze the sample\'s gene expression profile. It scores the expression activities of gene sets at a single\-sample level.


.. conda:package:: bioconductor-singscore

   |downloads_bioconductor-singscore| |docker_bioconductor-singscore|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.2.2-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-gseabase: ``>=1.52.0,<1.53.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-magrittr: 
   :depends r-matrixstats: 
   :depends r-plotly: 
   :depends r-plyr: 
   :depends r-rcolorbrewer: 
   :depends r-reshape: 
   :depends r-reshape2: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-singscore

   and update with::

      conda update bioconductor-singscore

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-singscore:<tag>

   (see `bioconductor-singscore/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-singscore| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-singscore.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-singscore
   :alt:   (downloads)
.. |docker_bioconductor-singscore| image:: https://quay.io/repository/biocontainers/bioconductor-singscore/status
   :target: https://quay.io/repository/biocontainers/bioconductor-singscore
.. _`bioconductor-singscore/tags`: https://quay.io/repository/biocontainers/bioconductor-singscore?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-singscore/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-singscore/README.html