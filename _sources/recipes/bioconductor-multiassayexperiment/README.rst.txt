:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-multiassayexperiment'
.. highlight: bash

bioconductor-multiassayexperiment
=================================

.. conda:recipe:: bioconductor-multiassayexperiment
   :replaces_section_title:
   :noindex:

   Software for the integration of multi\-omics experiments in Bioconductor

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/MultiAssayExperiment.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-multiassayexperiment <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-multiassayexperiment>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-multiassayexperiment/meta.yaml>`_
   :links: biotools: :biotools:`multiassayexperiment`, doi: :doi:`10.1101/144774`

   MultiAssayExperiment harmonizes data management of multiple experimental assays performed on an overlapping set of specimens. It provides a familiar Bioconductor user experience by extending concepts from SummarizedExperiment\, supporting an open\-ended mix of standard data classes for individual assays\, and allowing subsetting by genomic ranges or rownames. Facilities are provided for reshaping data into wide and long formats for adaptability to graphing and downstream analysis.


.. conda:package:: bioconductor-multiassayexperiment

   |downloads_bioconductor-multiassayexperiment| |docker_bioconductor-multiassayexperiment|

   :versions:
      
      

      ``1.16.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.4-0``,  ``1.8.1-0``,  ``1.6.0-0``,  ``1.4.9-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-multiassayexperiment

   and update with::

      conda update bioconductor-multiassayexperiment

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-multiassayexperiment:<tag>

   (see `bioconductor-multiassayexperiment/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-multiassayexperiment| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-multiassayexperiment.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-multiassayexperiment
   :alt:   (downloads)
.. |docker_bioconductor-multiassayexperiment| image:: https://quay.io/repository/biocontainers/bioconductor-multiassayexperiment/status
   :target: https://quay.io/repository/biocontainers/bioconductor-multiassayexperiment
.. _`bioconductor-multiassayexperiment/tags`: https://quay.io/repository/biocontainers/bioconductor-multiassayexperiment?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-multiassayexperiment/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-multiassayexperiment/README.html