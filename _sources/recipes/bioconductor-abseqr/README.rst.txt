:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-abseqr'
.. highlight: bash

bioconductor-abseqr
===================

.. conda:recipe:: bioconductor-abseqr
   :replaces_section_title:
   :noindex:

   Reporting and data analysis functionalities for Rep\-Seq datasets of antibody libraries

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/abseqR.html
   :license: GPL-3 | file LICENSE
   :recipe: /`bioconductor-abseqr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-abseqr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-abseqr/meta.yaml>`_

   AbSeq is a comprehensive bioinformatic pipeline for the analysis of sequencing datasets generated from antibody libraries and abseqR is one of its packages. abseqR empowers the users of abseqPy \(https\:\/\/github.com\/malhamdoosh\/abseqPy\) with plotting and reporting capabilities and allows them to generate interactive HTML reports for the convenience of viewing and sharing with other researchers. Additionally\, abseqR extends abseqPy to compare multiple repertoire analyses and perform further downstream analysis on its output.


.. conda:package:: bioconductor-abseqr

   |downloads_bioconductor-abseqr| |docker_bioconductor-abseqr|

   :versions:
      
      

      ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.2.0-0``,  ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-biocstyle: ``>=2.18.0,<2.19.0``
   :depends pandoc: ``>=1.19.2.1``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-circlize: 
   :depends r-flexdashboard: 
   :depends r-ggcorrplot: 
   :depends r-ggdendro: 
   :depends r-ggplot2: 
   :depends r-gridextra: 
   :depends r-knitr: 
   :depends r-plotly: 
   :depends r-plyr: 
   :depends r-png: 
   :depends r-rcolorbrewer: 
   :depends r-reshape2: 
   :depends r-rmarkdown: 
   :depends r-stringr: 
   :depends r-vegan: 
   :depends r-venndiagram: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-abseqr

   and update with::

      conda update bioconductor-abseqr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-abseqr:<tag>

   (see `bioconductor-abseqr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-abseqr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-abseqr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-abseqr
   :alt:   (downloads)
.. |docker_bioconductor-abseqr| image:: https://quay.io/repository/biocontainers/bioconductor-abseqr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-abseqr
.. _`bioconductor-abseqr/tags`: https://quay.io/repository/biocontainers/bioconductor-abseqr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-abseqr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-abseqr/README.html