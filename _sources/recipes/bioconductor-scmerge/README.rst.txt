:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-scmerge'
.. highlight: bash

bioconductor-scmerge
====================

.. conda:recipe:: bioconductor-scmerge
   :replaces_section_title:
   :noindex:

   scMerge\: Merging multiple batches of scRNA\-seq data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/scMerge.html
   :license: GPL-3
   :recipe: /`bioconductor-scmerge <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scmerge>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scmerge/meta.yaml>`_

   Like all gene expression data\, single\-cell RNA\-seq \(scRNA\-Seq\) data suffers from batch effects and other unwanted variations that makes accurate biological interpretations difficult. The scMerge method leverages factor analysis\, stably expressed genes \(SEGs\) and \(pseudo\-\) replicates to remove unwanted variations and merge multiple scRNA\-Seq data. This package contains all the necessary functions in the scMerge pipeline\, including the identification of SEGs\, replication\-identification methods\, and merging of scRNA\-Seq data.


.. conda:package:: bioconductor-scmerge

   |downloads_bioconductor-scmerge| |docker_bioconductor-scmerge|

   :versions:
      
      

      ``1.6.0-1``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-1``

      

   
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-biocsingular: ``>=1.6.0,<1.7.0``
   :depends bioconductor-delayedarray: ``>=0.16.0,<0.17.0``
   :depends bioconductor-delayedmatrixstats: ``>=1.12.0,<1.13.0``
   :depends bioconductor-m3drop: ``>=1.16.0,<1.17.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-singlecellexperiment: ``>=1.12.0,<1.13.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cluster: 
   :depends r-distr: 
   :depends r-igraph: 
   :depends r-pdist: 
   :depends r-proxy: 
   :depends r-ruv: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-scmerge

   and update with::

      conda update bioconductor-scmerge

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-scmerge:<tag>

   (see `bioconductor-scmerge/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-scmerge| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-scmerge.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-scmerge
   :alt:   (downloads)
.. |docker_bioconductor-scmerge| image:: https://quay.io/repository/biocontainers/bioconductor-scmerge/status
   :target: https://quay.io/repository/biocontainers/bioconductor-scmerge
.. _`bioconductor-scmerge/tags`: https://quay.io/repository/biocontainers/bioconductor-scmerge?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-scmerge/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-scmerge/README.html