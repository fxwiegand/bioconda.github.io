:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tarseqqc'
.. highlight: bash

bioconductor-tarseqqc
=====================

.. conda:recipe:: bioconductor-tarseqqc
   :replaces_section_title:
   :noindex:

   TARgeted SEQuencing Experiment Quality Control

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/TarSeqQC.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-tarseqqc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tarseqqc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tarseqqc/meta.yaml>`_
   :links: biotools: :biotools:`tarseqqc`

   The package allows the representation of targeted experiment in R. This is based on current packages and incorporates functions to do a quality control over this kind of experiments and a fast exploration of the sequenced regions. An xlsx file is generated as output.


.. conda:package:: bioconductor-tarseqqc

   |downloads_bioconductor-tarseqqc| |docker_bioconductor-tarseqqc|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.20.0-1</code>,  <code>1.20.0-0</code>,  <code>1.18.0-0</code>,  <code>1.16.0-0</code>,  <code>1.14.0-1</code>,  <code>1.12.0-0</code>,  <code>1.10.0-0</code>,  <code>1.8.0-0</code>,  <code>1.6.2-0</code>,  </span></summary>
      

      ``1.20.0-1``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-1``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.2-0``,  ``1.6.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-cowplot: 
   :depends r-ggplot2: 
   :depends r-hmisc: 
   :depends r-openxlsx: 
   :depends r-plyr: 
   :depends r-reshape2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tarseqqc

   and update with::

      conda update bioconductor-tarseqqc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tarseqqc:<tag>

   (see `bioconductor-tarseqqc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tarseqqc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tarseqqc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tarseqqc
   :alt:   (downloads)
.. |docker_bioconductor-tarseqqc| image:: https://quay.io/repository/biocontainers/bioconductor-tarseqqc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tarseqqc
.. _`bioconductor-tarseqqc/tags`: https://quay.io/repository/biocontainers/bioconductor-tarseqqc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tarseqqc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tarseqqc/README.html