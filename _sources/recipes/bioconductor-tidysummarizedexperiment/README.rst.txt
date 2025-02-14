:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tidysummarizedexperiment'
.. highlight: bash

bioconductor-tidysummarizedexperiment
=====================================

.. conda:recipe:: bioconductor-tidysummarizedexperiment
   :replaces_section_title:
   :noindex:

   Brings SummarizedExperiment to the Tidyverse

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/tidySummarizedExperiment.html
   :license: GPL-3
   :recipe: /`bioconductor-tidysummarizedexperiment <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tidysummarizedexperiment>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tidysummarizedexperiment/meta.yaml>`_

   tidySummarizedExperiment is an adapter that abstracts the \'SingleCellExperiment\' container in the form of tibble and allows the data manipulation\, plotting and nesting using \'tidyverse\'


.. conda:package:: bioconductor-tidysummarizedexperiment

   |downloads_bioconductor-tidysummarizedexperiment| |docker_bioconductor-tidysummarizedexperiment|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cli: 
   :depends r-dplyr: 
   :depends r-ellipsis: 
   :depends r-fansi: 
   :depends r-ggplot2: 
   :depends r-lifecycle: 
   :depends r-magrittr: 
   :depends r-pillar: 
   :depends r-plotly: 
   :depends r-purrr: 
   :depends r-rlang: 
   :depends r-stringr: 
   :depends r-tibble: ``>=3.0.4``
   :depends r-tidyr: 
   :depends r-tidyselect: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tidysummarizedexperiment

   and update with::

      conda update bioconductor-tidysummarizedexperiment

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tidysummarizedexperiment:<tag>

   (see `bioconductor-tidysummarizedexperiment/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tidysummarizedexperiment| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tidysummarizedexperiment.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tidysummarizedexperiment
   :alt:   (downloads)
.. |docker_bioconductor-tidysummarizedexperiment| image:: https://quay.io/repository/biocontainers/bioconductor-tidysummarizedexperiment/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tidysummarizedexperiment
.. _`bioconductor-tidysummarizedexperiment/tags`: https://quay.io/repository/biocontainers/bioconductor-tidysummarizedexperiment?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tidysummarizedexperiment/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tidysummarizedexperiment/README.html