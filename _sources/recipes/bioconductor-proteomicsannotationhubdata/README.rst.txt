:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-proteomicsannotationhubdata'
.. highlight: bash

bioconductor-proteomicsannotationhubdata
========================================

.. conda:recipe:: bioconductor-proteomicsannotationhubdata
   :replaces_section_title:
   :noindex:

   Transform public proteomics data resources into Bioconductor Data Structures

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ProteomicsAnnotationHubData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-proteomicsannotationhubdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-proteomicsannotationhubdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-proteomicsannotationhubdata/meta.yaml>`_
   :links: biotools: :biotools:`proteomicsannotationhubdata`, doi: :doi:`10.1038/nmeth.3252`

   These recipes convert a variety and a growing number of public proteomics data sets into easily\-used standard Bioconductor data structures.


.. conda:package:: bioconductor-proteomicsannotationhubdata

   |downloads_bioconductor-proteomicsannotationhubdata| |docker_bioconductor-proteomicsannotationhubdata|

   :versions:
      
      

      ``1.20.0-1``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-1``,  ``1.12.0-0``,  ``1.8.0-0``

      

   
   :depends bioconductor-annotationhub: ``>=2.22.0,<2.23.0``
   :depends bioconductor-annotationhubdata: ``>=1.20.0,<1.21.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-msnbase: ``>=2.16.0,<2.17.0``
   :depends bioconductor-mzr: ``>=2.24.0,<2.25.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-biocmanager: 
   :depends r-rcurl: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-proteomicsannotationhubdata

   and update with::

      conda update bioconductor-proteomicsannotationhubdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-proteomicsannotationhubdata:<tag>

   (see `bioconductor-proteomicsannotationhubdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-proteomicsannotationhubdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-proteomicsannotationhubdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-proteomicsannotationhubdata
   :alt:   (downloads)
.. |docker_bioconductor-proteomicsannotationhubdata| image:: https://quay.io/repository/biocontainers/bioconductor-proteomicsannotationhubdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-proteomicsannotationhubdata
.. _`bioconductor-proteomicsannotationhubdata/tags`: https://quay.io/repository/biocontainers/bioconductor-proteomicsannotationhubdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-proteomicsannotationhubdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-proteomicsannotationhubdata/README.html