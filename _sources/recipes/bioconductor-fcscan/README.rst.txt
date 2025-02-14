:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fcscan'
.. highlight: bash

bioconductor-fcscan
===================

.. conda:recipe:: bioconductor-fcscan
   :replaces_section_title:
   :noindex:

   fcScan for detecting clusters of coordinates with user defined options

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/fcScan.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-fcscan <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fcscan>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fcscan/meta.yaml>`_

   This package is used to detect combination of genomic coordinates falling within a user defined window size along with user defined overlap between identified neighboring clusters. It can be used for genomic data where the clusters are built on a specific chromosome or specific strand. Clustering can be performed with a \"greedy\" option allowing thus the presence of additional sites within the allowed window size.


.. conda:package:: bioconductor-fcscan

   |downloads_bioconductor-fcscan| |docker_bioconductor-fcscan|

   :versions:
      
      

      ``1.4.0-1``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends bioconductor-variantannotation: ``>=1.36.0,<1.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-plyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-fcscan

   and update with::

      conda update bioconductor-fcscan

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fcscan:<tag>

   (see `bioconductor-fcscan/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fcscan| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fcscan.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fcscan
   :alt:   (downloads)
.. |docker_bioconductor-fcscan| image:: https://quay.io/repository/biocontainers/bioconductor-fcscan/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fcscan
.. _`bioconductor-fcscan/tags`: https://quay.io/repository/biocontainers/bioconductor-fcscan?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fcscan/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fcscan/README.html