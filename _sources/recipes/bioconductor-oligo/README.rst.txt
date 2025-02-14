:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-oligo'
.. highlight: bash

bioconductor-oligo
==================

.. conda:recipe:: bioconductor-oligo
   :replaces_section_title:
   :noindex:

   Preprocessing tools for oligonucleotide arrays

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/oligo.html
   :license: LGPL (>= 2)
   :recipe: /`bioconductor-oligo <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-oligo>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-oligo/meta.yaml>`_
   :links: biotools: :biotools:`oligo`

   A package to analyze oligonucleotide arrays \(expression\/SNP\/tiling\/exon\) at probe\-level. It currently supports Affymetrix \(CEL files\) and NimbleGen arrays \(XYS files\).


.. conda:package:: bioconductor-oligo

   |downloads_bioconductor-oligo| |docker_bioconductor-oligo|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.54.1-0</code>,  <code>1.54.0-0</code>,  <code>1.52.0-0</code>,  <code>1.50.0-0</code>,  <code>1.48.0-1</code>,  <code>1.46.0-0</code>,  <code>1.44.0-0</code>,  <code>1.42.0-0</code>,  <code>1.40.2-0</code>,  </span></summary>
      

      ``1.54.1-0``,  ``1.54.0-0``,  ``1.52.0-0``,  ``1.50.0-0``,  ``1.48.0-1``,  ``1.46.0-0``,  ``1.44.0-0``,  ``1.42.0-0``,  ``1.40.2-0``,  ``1.40.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-affxparser: ``>=1.62.0,<1.63.0``
   :depends bioconductor-affyio: ``>=1.60.0,<1.61.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-oligoclasses: ``>=1.52.0,<1.53.0``
   :depends bioconductor-preprocesscore: ``>=1.52.0,<1.53.0``
   :depends bioconductor-zlibbioc: ``>=1.36.0,<1.37.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dbi: ``>=0.3.1``
   :depends r-ff: 
   :depends r-rsqlite: ``>=1.0.0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-oligo

   and update with::

      conda update bioconductor-oligo

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-oligo:<tag>

   (see `bioconductor-oligo/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-oligo| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-oligo.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-oligo
   :alt:   (downloads)
.. |docker_bioconductor-oligo| image:: https://quay.io/repository/biocontainers/bioconductor-oligo/status
   :target: https://quay.io/repository/biocontainers/bioconductor-oligo
.. _`bioconductor-oligo/tags`: https://quay.io/repository/biocontainers/bioconductor-oligo?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-oligo/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-oligo/README.html