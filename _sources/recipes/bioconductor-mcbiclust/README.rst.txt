:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mcbiclust'
.. highlight: bash

bioconductor-mcbiclust
======================

.. conda:recipe:: bioconductor-mcbiclust
   :replaces_section_title:
   :noindex:

   Massive correlating biclusters for gene expression data and associated methods

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/MCbiclust.html
   :license: GPL-2
   :recipe: /`bioconductor-mcbiclust <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mcbiclust>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mcbiclust/meta.yaml>`_

   Custom made algorithm and associated methods for finding\, visualising and analysing biclusters in large gene expression data sets. Algorithm is based on with a supplied gene set of size n\, finding the maximum strength correlation matrix containing m samples from the data set.


.. conda:package:: bioconductor-mcbiclust

   |downloads_bioconductor-mcbiclust| |docker_bioconductor-mcbiclust|

   :versions:
      
      

      ``1.14.0-1``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.0-1``,  ``1.6.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-go.db: ``>=3.12.1,<3.13.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cluster: 
   :depends r-ggally: 
   :depends r-ggplot2: 
   :depends r-scales: 
   :depends r-wgcna: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mcbiclust

   and update with::

      conda update bioconductor-mcbiclust

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mcbiclust:<tag>

   (see `bioconductor-mcbiclust/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mcbiclust| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mcbiclust.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mcbiclust
   :alt:   (downloads)
.. |docker_bioconductor-mcbiclust| image:: https://quay.io/repository/biocontainers/bioconductor-mcbiclust/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mcbiclust
.. _`bioconductor-mcbiclust/tags`: https://quay.io/repository/biocontainers/bioconductor-mcbiclust?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mcbiclust/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mcbiclust/README.html