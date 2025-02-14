:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fithic'
.. highlight: bash

bioconductor-fithic
===================

.. conda:recipe:: bioconductor-fithic
   :replaces_section_title:
   :noindex:

   Confidence estimation for intra\-chromosomal contact maps

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/FitHiC.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-fithic <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fithic>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fithic/meta.yaml>`_
   :links: biotools: :biotools:`fithic`, doi: :doi:`10.1101/gr.160374`

   Fit\-Hi\-C is a tool for assigning statistical confidence estimates to intra\-chromosomal contact maps produced by genome\-wide genome architecture assays such as Hi\-C.


.. conda:package:: bioconductor-fithic

   |downloads_bioconductor-fithic| |docker_bioconductor-fithic|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.16.0-1</code>,  <code>1.16.0-0</code>,  <code>1.14.0-0</code>,  <code>1.12.0-0</code>,  <code>1.10.0-1</code>,  <code>1.10.0-0</code>,  <code>1.8.0-0</code>,  <code>1.6.0-0</code>,  <code>1.4.0-0</code>,  </span></summary>
      

      ``1.16.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-fdrtool: 
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-fithic

   and update with::

      conda update bioconductor-fithic

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fithic:<tag>

   (see `bioconductor-fithic/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fithic| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fithic.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fithic
   :alt:   (downloads)
.. |docker_bioconductor-fithic| image:: https://quay.io/repository/biocontainers/bioconductor-fithic/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fithic
.. _`bioconductor-fithic/tags`: https://quay.io/repository/biocontainers/bioconductor-fithic?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fithic/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fithic/README.html