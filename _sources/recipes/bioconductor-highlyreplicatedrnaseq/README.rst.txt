:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-highlyreplicatedrnaseq'
.. highlight: bash

bioconductor-highlyreplicatedrnaseq
===================================

.. conda:recipe:: bioconductor-highlyreplicatedrnaseq
   :replaces_section_title:
   :noindex:

   Collection of Bulk RNA\-Seq Experiments With Many Replicates

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/HighlyReplicatedRNASeq.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-highlyreplicatedrnaseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-highlyreplicatedrnaseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-highlyreplicatedrnaseq/meta.yaml>`_

   Gene\-level count matrix data for bulk RNA\-seq dataset with many replicates. The data are provided as easy to use SummarizedExperiment objects. The source data that is made accessible through this package comes from https\:\/\/github.com\/bartongroup\/profDGE48.


.. conda:package:: bioconductor-highlyreplicatedrnaseq

   |downloads_bioconductor-highlyreplicatedrnaseq| |docker_bioconductor-highlyreplicatedrnaseq|

   :versions:
      
      

      ``1.2.0-1``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-experimenthub: ``>=1.16.0,<1.17.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-highlyreplicatedrnaseq

   and update with::

      conda update bioconductor-highlyreplicatedrnaseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-highlyreplicatedrnaseq:<tag>

   (see `bioconductor-highlyreplicatedrnaseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-highlyreplicatedrnaseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-highlyreplicatedrnaseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-highlyreplicatedrnaseq
   :alt:   (downloads)
.. |docker_bioconductor-highlyreplicatedrnaseq| image:: https://quay.io/repository/biocontainers/bioconductor-highlyreplicatedrnaseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-highlyreplicatedrnaseq
.. _`bioconductor-highlyreplicatedrnaseq/tags`: https://quay.io/repository/biocontainers/bioconductor-highlyreplicatedrnaseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-highlyreplicatedrnaseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-highlyreplicatedrnaseq/README.html