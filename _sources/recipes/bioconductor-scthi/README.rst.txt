:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-scthi'
.. highlight: bash

bioconductor-scthi
==================

.. conda:recipe:: bioconductor-scthi
   :replaces_section_title:
   :noindex:

   Indentification of significantly activated ligand\-receptor interactions across clusters of cells from single\-cell RNA sequencing data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/scTHI.html
   :license: GPL-2
   :recipe: /`bioconductor-scthi <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scthi>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-scthi/meta.yaml>`_

   scTHI is an R package to identify active pairs of ligand\-receptors from single cells in order to study\,among others\, tumor\-host interactions. scTHI contains a set of signatures to classify cells from the tumor microenvironment.


.. conda:package:: bioconductor-scthi

   |downloads_bioconductor-scthi| |docker_bioconductor-scthi|

   :versions:
      
      

      ``1.2.0-1``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-rtsne: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-scthi

   and update with::

      conda update bioconductor-scthi

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-scthi:<tag>

   (see `bioconductor-scthi/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-scthi| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-scthi.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-scthi
   :alt:   (downloads)
.. |docker_bioconductor-scthi| image:: https://quay.io/repository/biocontainers/bioconductor-scthi/status
   :target: https://quay.io/repository/biocontainers/bioconductor-scthi
.. _`bioconductor-scthi/tags`: https://quay.io/repository/biocontainers/bioconductor-scthi?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-scthi/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-scthi/README.html