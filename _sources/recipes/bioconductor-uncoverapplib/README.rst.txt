:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-uncoverapplib'
.. highlight: bash

bioconductor-uncoverapplib
==========================

.. conda:recipe:: bioconductor-uncoverapplib
   :replaces_section_title:
   :noindex:

   Interactive graphical application for clinical assessment of sequence coverage at the base\-pair level

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/uncoverappLib.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-uncoverapplib <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-uncoverapplib>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-uncoverapplib/meta.yaml>`_

   a Shiny application containing a suite of graphical and statistical tools to support clinical assessment of low coverage regions.It displays three web pages each providing a different analysis module\: Coverage analysis\, calculate AF by allele frequency app and binomial distribution.


.. conda:package:: bioconductor-uncoverapplib

   |downloads_bioconductor-uncoverapplib| |docker_bioconductor-uncoverapplib|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-biocfilecache: ``>=1.14.0,<1.15.0``
   :depends bioconductor-bsgenome.hsapiens.ucsc.hg19: ``>=1.4.0,<1.5.0``
   :depends bioconductor-ensdb.hsapiens.v75: ``>=2.99.0,<2.100.0``
   :depends bioconductor-ensdb.hsapiens.v86: ``>=2.99.0,<2.100.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-gviz: ``>=1.34.0,<1.35.0``
   :depends bioconductor-homo.sapiens: ``>=1.3.0,<1.4.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends bioconductor-organismdbi: ``>=1.32.0,<1.33.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-txdb.hsapiens.ucsc.hg19.knowngene: ``>=3.2.0,<3.3.0``
   :depends bioconductor-txdb.hsapiens.ucsc.hg38.knowngene: ``>=3.10.0,<3.11.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-condformat: 
   :depends r-dt: 
   :depends r-markdown: 
   :depends r-openxlsx: 
   :depends r-processx: 
   :depends r-rappdirs: 
   :depends r-rlist: 
   :depends r-shiny: 
   :depends r-shinybs: 
   :depends r-shinycssloaders: 
   :depends r-shinyjs: 
   :depends r-shinywidgets: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-uncoverapplib

   and update with::

      conda update bioconductor-uncoverapplib

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-uncoverapplib:<tag>

   (see `bioconductor-uncoverapplib/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-uncoverapplib| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-uncoverapplib.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-uncoverapplib
   :alt:   (downloads)
.. |docker_bioconductor-uncoverapplib| image:: https://quay.io/repository/biocontainers/bioconductor-uncoverapplib/status
   :target: https://quay.io/repository/biocontainers/bioconductor-uncoverapplib
.. _`bioconductor-uncoverapplib/tags`: https://quay.io/repository/biocontainers/bioconductor-uncoverapplib?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-uncoverapplib/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-uncoverapplib/README.html