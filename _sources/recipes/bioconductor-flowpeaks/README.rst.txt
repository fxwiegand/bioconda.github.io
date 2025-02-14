:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-flowpeaks'
.. highlight: bash

bioconductor-flowpeaks
======================

.. conda:recipe:: bioconductor-flowpeaks
   :replaces_section_title:
   :noindex:

   An R package for flow data clustering

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/flowPeaks.html
   :license: Artistic-1.0
   :recipe: /`bioconductor-flowpeaks <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowpeaks>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-flowpeaks/meta.yaml>`_
   :links: biotools: :biotools:`flowpeaks`

   A fast and automatic clustering to classify the cells into subpopulations based on finding the peaks from the overall density function generated by K\-means.


.. conda:package:: bioconductor-flowpeaks

   |downloads_bioconductor-flowpeaks| |docker_bioconductor-flowpeaks|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.36.0-1</code>,  <code>1.36.0-0</code>,  <code>1.34.0-0</code>,  <code>1.32.0-0</code>,  <code>1.30.0-1</code>,  <code>1.30.0-0</code>,  <code>1.28.1-0</code>,  <code>1.28.0-0</code>,  <code>1.26.0-0</code>,  </span></summary>
      

      ``1.36.0-1``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``,  ``1.30.0-1``,  ``1.30.0-0``,  ``1.28.1-0``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.20.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends gsl: ``>=2.6,<2.7.0a0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-flowpeaks

   and update with::

      conda update bioconductor-flowpeaks

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-flowpeaks:<tag>

   (see `bioconductor-flowpeaks/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-flowpeaks| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-flowpeaks.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-flowpeaks
   :alt:   (downloads)
.. |docker_bioconductor-flowpeaks| image:: https://quay.io/repository/biocontainers/bioconductor-flowpeaks/status
   :target: https://quay.io/repository/biocontainers/bioconductor-flowpeaks
.. _`bioconductor-flowpeaks/tags`: https://quay.io/repository/biocontainers/bioconductor-flowpeaks?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-flowpeaks/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-flowpeaks/README.html