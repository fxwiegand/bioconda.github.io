:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-summarizedbenchmark'
.. highlight: bash

bioconductor-summarizedbenchmark
================================

.. conda:recipe:: bioconductor-summarizedbenchmark
   :replaces_section_title:
   :noindex:

   Classes and methods for performing benchmark comparisons

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/SummarizedBenchmark.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-summarizedbenchmark <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-summarizedbenchmark>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-summarizedbenchmark/meta.yaml>`_

   This package defines the BenchDesign and SummarizedBenchmark classes for building\, executing\, and evaluating benchmark experiments of computational methods. The SummarizedBenchmark class extends the RangedSummarizedExperiment object\, and is designed to provide infrastructure to store and compare the results of applying different methods to a shared data set. This class provides an integrated interface to store metadata such as method parameters and software versions as well as ground truths \(when these are available\) and evaluation metrics.


.. conda:package:: bioconductor-summarizedbenchmark

   |downloads_bioconductor-summarizedbenchmark| |docker_bioconductor-summarizedbenchmark|

   :versions:
      
      

      ``2.8.0-1``,  ``2.8.0-0``,  ``2.6.0-0``,  ``2.4.0-0``,  ``2.2.2-0``,  ``2.0.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-crayon: 
   :depends r-digest: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-mclust: 
   :depends r-rlang: 
   :depends r-sessioninfo: 
   :depends r-stringr: 
   :depends r-tibble: 
   :depends r-tidyr: 
   :depends r-upsetr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-summarizedbenchmark

   and update with::

      conda update bioconductor-summarizedbenchmark

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-summarizedbenchmark:<tag>

   (see `bioconductor-summarizedbenchmark/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-summarizedbenchmark| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-summarizedbenchmark.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-summarizedbenchmark
   :alt:   (downloads)
.. |docker_bioconductor-summarizedbenchmark| image:: https://quay.io/repository/biocontainers/bioconductor-summarizedbenchmark/status
   :target: https://quay.io/repository/biocontainers/bioconductor-summarizedbenchmark
.. _`bioconductor-summarizedbenchmark/tags`: https://quay.io/repository/biocontainers/bioconductor-summarizedbenchmark?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-summarizedbenchmark/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-summarizedbenchmark/README.html