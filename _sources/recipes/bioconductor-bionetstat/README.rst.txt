:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bionetstat'
.. highlight: bash

bioconductor-bionetstat
=======================

.. conda:recipe:: bioconductor-bionetstat
   :replaces_section_title:
   :noindex:

   Biological Network Analysis

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/BioNetStat.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-bionetstat <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bionetstat>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bionetstat/meta.yaml>`_

   A package to perform differential network analysis\, differential node analysis \(differential coexpression analysis\)\, network and metabolic pathways view.


.. conda:package:: bioconductor-bionetstat

   |downloads_bioconductor-bionetstat| |docker_bioconductor-bionetstat|

   :versions:
      
      

      ``1.10.2-0``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.2.2-0``

      

   
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-pathview: ``>=1.30.0,<1.31.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dt: 
   :depends r-ggplot2: 
   :depends r-hmisc: 
   :depends r-igraph: 
   :depends r-knitr: 
   :depends r-pheatmap: 
   :depends r-plyr: 
   :depends r-psych: 
   :depends r-rcolorbrewer: 
   :depends r-rjsonio: 
   :depends r-shiny: 
   :depends r-shinybs: 
   :depends r-whisker: 
   :depends r-yaml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bionetstat

   and update with::

      conda update bioconductor-bionetstat

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bionetstat:<tag>

   (see `bioconductor-bionetstat/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bionetstat| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bionetstat.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bionetstat
   :alt:   (downloads)
.. |docker_bioconductor-bionetstat| image:: https://quay.io/repository/biocontainers/bioconductor-bionetstat/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bionetstat
.. _`bioconductor-bionetstat/tags`: https://quay.io/repository/biocontainers/bioconductor-bionetstat?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bionetstat/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bionetstat/README.html