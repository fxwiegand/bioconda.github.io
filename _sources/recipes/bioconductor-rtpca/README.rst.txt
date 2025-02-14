:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rtpca'
.. highlight: bash

bioconductor-rtpca
==================

.. conda:recipe:: bioconductor-rtpca
   :replaces_section_title:
   :noindex:

   Thermal proximity co\-aggregation with R

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/Rtpca.html
   :license: GPL-3
   :recipe: /`bioconductor-rtpca <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rtpca>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rtpca/meta.yaml>`_

   R package for performing thermal proximity co\-aggregation analysis with thermal proteome profiling datasets to analyse protein complex assembly and \(differential\) protein\-protein interactions across conditions.


.. conda:package:: bioconductor-rtpca

   |downloads_bioconductor-rtpca| |docker_bioconductor-rtpca|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dplyr: 
   :depends r-fdrtool: 
   :depends r-ggplot2: 
   :depends r-proc: 
   :depends r-tibble: 
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rtpca

   and update with::

      conda update bioconductor-rtpca

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rtpca:<tag>

   (see `bioconductor-rtpca/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rtpca| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rtpca.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rtpca
   :alt:   (downloads)
.. |docker_bioconductor-rtpca| image:: https://quay.io/repository/biocontainers/bioconductor-rtpca/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rtpca
.. _`bioconductor-rtpca/tags`: https://quay.io/repository/biocontainers/bioconductor-rtpca?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rtpca/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rtpca/README.html