:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tweedeseq'
.. highlight: bash

bioconductor-tweedeseq
======================

.. conda:recipe:: bioconductor-tweedeseq
   :replaces_section_title:
   :noindex:

   RNA\-seq data analysis using the Poisson\-Tweedie family of distributions

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/tweeDEseq.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-tweedeseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tweedeseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tweedeseq/meta.yaml>`_
   :links: biotools: :biotools:`tweedeseq`

   Differential expression analysis of RNA\-seq using the Poisson\-Tweedie family of distributions.


.. conda:package:: bioconductor-tweedeseq

   |downloads_bioconductor-tweedeseq| |docker_bioconductor-tweedeseq|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.36.0-1</code>,  <code>1.36.0-0</code>,  <code>1.34.0-0</code>,  <code>1.32.0-0</code>,  <code>1.30.0-1</code>,  <code>1.30.0-0</code>,  <code>1.28.1-0</code>,  <code>1.28.0-0</code>,  <code>1.26.0-0</code>,  </span></summary>
      

      ``1.36.0-1``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``,  ``1.30.0-1``,  ``1.30.0-0``,  ``1.28.1-0``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-cqn: ``>=1.36.0,<1.37.0``
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-mass: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tweedeseq

   and update with::

      conda update bioconductor-tweedeseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tweedeseq:<tag>

   (see `bioconductor-tweedeseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tweedeseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tweedeseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tweedeseq
   :alt:   (downloads)
.. |docker_bioconductor-tweedeseq| image:: https://quay.io/repository/biocontainers/bioconductor-tweedeseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tweedeseq
.. _`bioconductor-tweedeseq/tags`: https://quay.io/repository/biocontainers/bioconductor-tweedeseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tweedeseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tweedeseq/README.html