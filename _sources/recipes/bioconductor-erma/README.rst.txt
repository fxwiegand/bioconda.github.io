:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-erma'
.. highlight: bash

bioconductor-erma
=================

.. conda:recipe:: bioconductor-erma
   :replaces_section_title:
   :noindex:

   epigenomic road map adventures

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/erma.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-erma <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-erma>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-erma/meta.yaml>`_

   Software and data to support epigenomic road map adventures.


.. conda:package:: bioconductor-erma

   |downloads_bioconductor-erma| |docker_bioconductor-erma|

   :versions:
      
      

      ``1.6.0-1``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-1``,  ``0.14.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicfiles: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-homo.sapiens: ``>=1.3.0,<1.4.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-shiny: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-erma

   and update with::

      conda update bioconductor-erma

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-erma:<tag>

   (see `bioconductor-erma/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-erma| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-erma.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-erma
   :alt:   (downloads)
.. |docker_bioconductor-erma| image:: https://quay.io/repository/biocontainers/bioconductor-erma/status
   :target: https://quay.io/repository/biocontainers/bioconductor-erma
.. _`bioconductor-erma/tags`: https://quay.io/repository/biocontainers/bioconductor-erma?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-erma/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-erma/README.html