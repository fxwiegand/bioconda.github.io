:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chipxpress'
.. highlight: bash

bioconductor-chipxpress
=======================

.. conda:recipe:: bioconductor-chipxpress
   :replaces_section_title:
   :noindex:

   ChIPXpress\: enhanced transcription factor target gene identification from ChIP\-seq and ChIP\-chip data using publicly available gene expression profiles

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ChIPXpress.html
   :license: GPL(>=2)
   :recipe: /`bioconductor-chipxpress <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipxpress>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chipxpress/meta.yaml>`_
   :links: biotools: :biotools:`chipxpress`, doi: :doi:`10.1186/1471-2105-14-188`

   ChIPXpress takes as input predicted TF bound genes from ChIPx data and uses a corresponding database of gene expression profiles downloaded from NCBI GEO to rank the TF bound targets in order of which gene is most likely to be functional TF target.


.. conda:package:: bioconductor-chipxpress

   |downloads_bioconductor-chipxpress| |docker_bioconductor-chipxpress|

   :versions:
      
      

      ``1.34.0-0``,  ``1.30.0-1``,  ``1.28.0-1``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``

      

   
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-chipxpressdata: ``>=1.28.0,<1.29.0``
   :depends bioconductor-frma: ``>=1.42.0,<1.43.0``
   :depends bioconductor-geoquery: ``>=2.58.0,<2.59.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-biganalytics: 
   :depends r-bigmemory: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chipxpress

   and update with::

      conda update bioconductor-chipxpress

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chipxpress:<tag>

   (see `bioconductor-chipxpress/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chipxpress| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chipxpress.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chipxpress
   :alt:   (downloads)
.. |docker_bioconductor-chipxpress| image:: https://quay.io/repository/biocontainers/bioconductor-chipxpress/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chipxpress
.. _`bioconductor-chipxpress/tags`: https://quay.io/repository/biocontainers/bioconductor-chipxpress?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chipxpress/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chipxpress/README.html