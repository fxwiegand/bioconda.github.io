:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-arrmnormalization'
.. highlight: bash

bioconductor-arrmnormalization
==============================

.. conda:recipe:: bioconductor-arrmnormalization
   :replaces_section_title:
   :noindex:

   Adaptive Robust Regression normalization for Illumina methylation data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ARRmNormalization.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-arrmnormalization <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-arrmnormalization>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-arrmnormalization/meta.yaml>`_
   :links: biotools: :biotools:`arrmnormalization`, doi: :doi:`10.1186/s13059-014-0503-2`

   Perform the Adaptive Robust Regression method \(ARRm\) for the normalization of methylation data from the Illumina Infinium HumanMethylation 450k assay.


.. conda:package:: bioconductor-arrmnormalization

   |downloads_bioconductor-arrmnormalization| |docker_bioconductor-arrmnormalization|

   :versions:
      
      

      ``1.30.0-2``,  ``1.30.0-0``,  ``1.28.0-0``,  ``1.26.0-1``,  ``1.24.0-1``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-0``

      

   
   :depends bioconductor-arrmdata: ``>=1.26.0,<1.27.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-arrmnormalization

   and update with::

      conda update bioconductor-arrmnormalization

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-arrmnormalization:<tag>

   (see `bioconductor-arrmnormalization/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-arrmnormalization| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-arrmnormalization.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-arrmnormalization
   :alt:   (downloads)
.. |docker_bioconductor-arrmnormalization| image:: https://quay.io/repository/biocontainers/bioconductor-arrmnormalization/status
   :target: https://quay.io/repository/biocontainers/bioconductor-arrmnormalization
.. _`bioconductor-arrmnormalization/tags`: https://quay.io/repository/biocontainers/bioconductor-arrmnormalization?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-arrmnormalization/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-arrmnormalization/README.html