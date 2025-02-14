:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-sbgnview.data'
.. highlight: bash

bioconductor-sbgnview.data
==========================

.. conda:recipe:: bioconductor-sbgnview.data
   :replaces_section_title:
   :noindex:

   Demo gene expression datasets for SBGNview package

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/SBGNview.data.html
   :license: AGPL-3
   :recipe: /`bioconductor-sbgnview.data <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sbgnview.data>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sbgnview.data/meta.yaml>`_

   This package contains\: 1. A microarray gene expression dataset from a human breast cancer study. 2. A RNA\-Seq gene expression dataset from a mouse study on IFNG knockout. 3. ID mapping tables between gene IDs and SBGN\-ML file glyph IDs. 4. Percent of orthologs detected in other species of the genes in a pathway. Cutoffs of this percentage for defining if a pathway exists in another species. 5. XML text of SBGN\-ML files for all pre\-collected pathways.


.. conda:package:: bioconductor-sbgnview.data

   |downloads_bioconductor-sbgnview.data| |docker_bioconductor-sbgnview.data|

   :versions:
      
      

      ``1.4.1-0``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-bookdown: 
   :depends r-knitr: 
   :depends r-rmarkdown: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-sbgnview.data

   and update with::

      conda update bioconductor-sbgnview.data

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-sbgnview.data:<tag>

   (see `bioconductor-sbgnview.data/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-sbgnview.data| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-sbgnview.data.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-sbgnview.data
   :alt:   (downloads)
.. |docker_bioconductor-sbgnview.data| image:: https://quay.io/repository/biocontainers/bioconductor-sbgnview.data/status
   :target: https://quay.io/repository/biocontainers/bioconductor-sbgnview.data
.. _`bioconductor-sbgnview.data/tags`: https://quay.io/repository/biocontainers/bioconductor-sbgnview.data?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-sbgnview.data/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-sbgnview.data/README.html