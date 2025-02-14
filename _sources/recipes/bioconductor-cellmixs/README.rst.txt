:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-cellmixs'
.. highlight: bash

bioconductor-cellmixs
=====================

.. conda:recipe:: bioconductor-cellmixs
   :replaces_section_title:
   :noindex:

   Evaluate Cellspecific Mixing

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/CellMixS.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-cellmixs <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cellmixs>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-cellmixs/meta.yaml>`_

   CellMixS provides metrics and functions to evaluate batch effects\, data integration and batch effect correction in single cell trancriptome data with single cell resolution. Results can be visualized and summarised on different levels\, e.g. on cell\, celltype or dataset level.


.. conda:package:: bioconductor-cellmixs

   |downloads_bioconductor-cellmixs| |docker_bioconductor-cellmixs|

   :versions:
      
      

      ``1.6.1-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-1``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biocneighbors: ``>=1.8.0,<1.9.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-scater: ``>=1.18.0,<1.19.0``
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cowplot: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-ggridges: 
   :depends r-ksamples: 
   :depends r-magrittr: 
   :depends r-purrr: 
   :depends r-tidyr: 
   :depends r-viridis: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-cellmixs

   and update with::

      conda update bioconductor-cellmixs

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-cellmixs:<tag>

   (see `bioconductor-cellmixs/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-cellmixs| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-cellmixs.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-cellmixs
   :alt:   (downloads)
.. |docker_bioconductor-cellmixs| image:: https://quay.io/repository/biocontainers/bioconductor-cellmixs/status
   :target: https://quay.io/repository/biocontainers/bioconductor-cellmixs
.. _`bioconductor-cellmixs/tags`: https://quay.io/repository/biocontainers/bioconductor-cellmixs?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-cellmixs/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-cellmixs/README.html