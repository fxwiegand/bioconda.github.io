:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mbamethyl'
.. highlight: bash

bioconductor-mbamethyl
======================

.. conda:recipe:: bioconductor-mbamethyl
   :replaces_section_title:
   :noindex:

   Model\-based analysis of DNA methylation data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/MBAmethyl.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-mbamethyl <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mbamethyl>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mbamethyl/meta.yaml>`_
   :links: biotools: :biotools:`mbamethyl`, doi: :doi:`10.1111/biom.12422`

   This package provides a function for reconstructing DNA methylation values from raw measurements. It iteratively implements the group fused lars to smooth related\-by\-location methylation values and the constrained least squares to remove probe affinity effect across multiple sequences.


.. conda:package:: bioconductor-mbamethyl

   |downloads_bioconductor-mbamethyl| |docker_bioconductor-mbamethyl|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.24.0-1</code>,  <code>1.24.0-0</code>,  <code>1.22.0-0</code>,  <code>1.20.0-0</code>,  <code>1.18.0-1</code>,  <code>1.18.0-0</code>,  <code>1.16.0-0</code>,  <code>1.14.0-0</code>,  <code>1.12.0-0</code>,  </span></summary>
      

      ``1.24.0-1``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mbamethyl

   and update with::

      conda update bioconductor-mbamethyl

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mbamethyl:<tag>

   (see `bioconductor-mbamethyl/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mbamethyl| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mbamethyl.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mbamethyl
   :alt:   (downloads)
.. |docker_bioconductor-mbamethyl| image:: https://quay.io/repository/biocontainers/bioconductor-mbamethyl/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mbamethyl
.. _`bioconductor-mbamethyl/tags`: https://quay.io/repository/biocontainers/bioconductor-mbamethyl?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mbamethyl/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mbamethyl/README.html