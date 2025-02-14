:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-spatiallibd'
.. highlight: bash

bioconductor-spatiallibd
========================

.. conda:recipe:: bioconductor-spatiallibd
   :replaces_section_title:
   :noindex:

   LIBD Visium spatial transcriptomics human pilot data inspector

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/spatialLIBD.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-spatiallibd <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spatiallibd>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spatiallibd/meta.yaml>`_

   Inspect interactively the spatial transcriptomics 10x Genomics Visium data from Maynard\, Collado\-Torres et al\, 2020 analyzed by Lieber Institute for Brain Development researchers and collaborators.


.. conda:package:: bioconductor-spatiallibd

   |downloads_bioconductor-spatiallibd| |docker_bioconductor-spatiallibd|

   :versions:
      
      

      ``1.2.1-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-annotationhub: ``>=2.22.0,<2.23.0``
   :depends bioconductor-biocfilecache: ``>=1.14.0,<1.15.0``
   :depends bioconductor-experimenthub: ``>=1.16.0,<1.17.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-scater: ``>=1.18.0,<1.19.0``
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-spatialexperiment: ``>=1.0.0,<1.1.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends curl: ``>=7.76.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-benchmarkme: 
   :depends r-cowplot: 
   :depends r-dt: 
   :depends r-fields: 
   :depends r-ggplot2: 
   :depends r-golem: 
   :depends r-jsonlite: 
   :depends r-plotly: 
   :depends r-png: 
   :depends r-polychrome: 
   :depends r-rcolorbrewer: 
   :depends r-readbitmap: 
   :depends r-sessioninfo: 
   :depends r-shiny: 
   :depends r-shinywidgets: 
   :depends r-tibble: 
   :depends r-viridislite: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-spatiallibd

   and update with::

      conda update bioconductor-spatiallibd

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-spatiallibd:<tag>

   (see `bioconductor-spatiallibd/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-spatiallibd| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-spatiallibd.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-spatiallibd
   :alt:   (downloads)
.. |docker_bioconductor-spatiallibd| image:: https://quay.io/repository/biocontainers/bioconductor-spatiallibd/status
   :target: https://quay.io/repository/biocontainers/bioconductor-spatiallibd
.. _`bioconductor-spatiallibd/tags`: https://quay.io/repository/biocontainers/bioconductor-spatiallibd?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-spatiallibd/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-spatiallibd/README.html