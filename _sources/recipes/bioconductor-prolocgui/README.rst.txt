:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-prolocgui'
.. highlight: bash

bioconductor-prolocgui
======================

.. conda:recipe:: bioconductor-prolocgui
   :replaces_section_title:
   :noindex:

   Interactive visualisation of spatial proteomics data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/pRolocGUI.html
   :license: GPL-2
   :recipe: /`bioconductor-prolocgui <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-prolocgui>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-prolocgui/meta.yaml>`_
   :links: biotools: :biotools:`prolocgui`, doi: :doi:`10.1038/ncomms9992`

   The package pRolocGUI comprises functions to interactively visualise organelle \(spatial\) proteomics data on the basis of pRoloc\, pRolocdata and shiny.


.. conda:package:: bioconductor-prolocgui

   |downloads_bioconductor-prolocgui| |docker_bioconductor-prolocgui|

   :versions:
      
      

      ``2.0.0-1``,  ``2.0.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.16.0-0``,  ``1.12.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-msnbase: ``>=2.16.0,<2.17.0``
   :depends bioconductor-proloc: ``>=1.30.0,<1.31.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-colorspace: 
   :depends r-colourpicker: 
   :depends r-dplyr: 
   :depends r-dt: ``>=0.1.40``
   :depends r-ggplot2: 
   :depends r-scales: 
   :depends r-shiny: ``>=0.9.1``
   :depends r-shinydashboard: 
   :depends r-shinydashboardplus: 
   :depends r-shinyhelper: 
   :depends r-shinyjs: 
   :depends r-shinywidgets: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-prolocgui

   and update with::

      conda update bioconductor-prolocgui

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-prolocgui:<tag>

   (see `bioconductor-prolocgui/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-prolocgui| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-prolocgui.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-prolocgui
   :alt:   (downloads)
.. |docker_bioconductor-prolocgui| image:: https://quay.io/repository/biocontainers/bioconductor-prolocgui/status
   :target: https://quay.io/repository/biocontainers/bioconductor-prolocgui
.. _`bioconductor-prolocgui/tags`: https://quay.io/repository/biocontainers/bioconductor-prolocgui?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-prolocgui/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-prolocgui/README.html