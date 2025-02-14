:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-experimentsubset'
.. highlight: bash

bioconductor-experimentsubset
=============================

.. conda:recipe:: bioconductor-experimentsubset
   :replaces_section_title:
   :noindex:

   Manages subsets of data with Bioconductor Experiment objects

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ExperimentSubset.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-experimentsubset <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-experimentsubset>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-experimentsubset/meta.yaml>`_

   Experiment objects such as the SummarizedExperiment or SingleCellExperiment are data containers for one or more matrix\-like assays along with the associated row and column data. Often only a subset of the original data is needed for down\-stream analysis. For example\, filtering out poor quality samples will require excluding some columns before analysis. The ExperimentSubset object is a container to efficiently manage different subsets of the same data without having to make separate objects for each new subset.


.. conda:package:: bioconductor-experimentsubset

   |downloads_bioconductor-experimentsubset| |docker_bioconductor-experimentsubset|

   :versions:
      
      

      ``1.0.0-2``,  ``1.0.0-1``

      

   
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-matrix: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-experimentsubset

   and update with::

      conda update bioconductor-experimentsubset

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-experimentsubset:<tag>

   (see `bioconductor-experimentsubset/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-experimentsubset| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-experimentsubset.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-experimentsubset
   :alt:   (downloads)
.. |docker_bioconductor-experimentsubset| image:: https://quay.io/repository/biocontainers/bioconductor-experimentsubset/status
   :target: https://quay.io/repository/biocontainers/bioconductor-experimentsubset
.. _`bioconductor-experimentsubset/tags`: https://quay.io/repository/biocontainers/bioconductor-experimentsubset?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-experimentsubset/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-experimentsubset/README.html