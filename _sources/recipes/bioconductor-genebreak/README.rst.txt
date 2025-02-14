:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-genebreak'
.. highlight: bash

bioconductor-genebreak
======================

.. conda:recipe:: bioconductor-genebreak
   :replaces_section_title:
   :noindex:

   Gene Break Detection

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/GeneBreak.html
   :license: GPL-2
   :recipe: /`bioconductor-genebreak <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genebreak>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genebreak/meta.yaml>`_
   :links: biotools: :biotools:`genebreak`, doi: :doi:`10.12688/f1000research.9259.1`

   Recurrent breakpoint gene detection on copy number aberration profiles.


.. conda:package:: bioconductor-genebreak

   |downloads_bioconductor-genebreak| |docker_bioconductor-genebreak|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.20.0-1</code>,  <code>1.20.0-0</code>,  <code>1.18.0-0</code>,  <code>1.16.0-0</code>,  <code>1.14.0-1</code>,  <code>1.12.0-0</code>,  <code>1.10.0-0</code>,  <code>1.8.0-0</code>,  <code>1.6.0-0</code>,  </span></summary>
      

      ``1.20.0-1``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-1``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-cghbase: ``>=1.50.0,<1.51.0``
   :depends bioconductor-cghcall: ``>=2.52.0,<2.53.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-qdnaseq: ``>=1.26.0,<1.27.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-genebreak

   and update with::

      conda update bioconductor-genebreak

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-genebreak:<tag>

   (see `bioconductor-genebreak/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-genebreak| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-genebreak.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-genebreak
   :alt:   (downloads)
.. |docker_bioconductor-genebreak| image:: https://quay.io/repository/biocontainers/bioconductor-genebreak/status
   :target: https://quay.io/repository/biocontainers/bioconductor-genebreak
.. _`bioconductor-genebreak/tags`: https://quay.io/repository/biocontainers/bioconductor-genebreak?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-genebreak/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-genebreak/README.html