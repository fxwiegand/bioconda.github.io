:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-compartmap'
.. highlight: bash

bioconductor-compartmap
=======================

.. conda:recipe:: bioconductor-compartmap
   :replaces_section_title:
   :noindex:

   A\/B compartment inference from ATAC\-seq and methylation array data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/compartmap.html
   :license: GPL-3 + file LICENSE
   :recipe: /`bioconductor-compartmap <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-compartmap>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-compartmap/meta.yaml>`_

   Compartmap performs shrunken A\/B compartment inference from ATAC\-seq and methylation arrays.


.. conda:package:: bioconductor-compartmap

   |downloads_bioconductor-compartmap| |docker_bioconductor-compartmap|

   :versions:
      
      

      ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.0.2-0``

      

   
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-homo.sapiens: ``>=1.3.0,<1.4.0``
   :depends bioconductor-minfi: ``>=1.36.0,<1.37.0``
   :depends bioconductor-mixomics: ``>=6.14.0,<6.15.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-gtools: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-compartmap

   and update with::

      conda update bioconductor-compartmap

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-compartmap:<tag>

   (see `bioconductor-compartmap/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-compartmap| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-compartmap.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-compartmap
   :alt:   (downloads)
.. |docker_bioconductor-compartmap| image:: https://quay.io/repository/biocontainers/bioconductor-compartmap/status
   :target: https://quay.io/repository/biocontainers/bioconductor-compartmap
.. _`bioconductor-compartmap/tags`: https://quay.io/repository/biocontainers/bioconductor-compartmap?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-compartmap/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-compartmap/README.html