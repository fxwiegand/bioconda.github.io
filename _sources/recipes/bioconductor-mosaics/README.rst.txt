:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mosaics'
.. highlight: bash

bioconductor-mosaics
====================

.. conda:recipe:: bioconductor-mosaics
   :replaces_section_title:
   :noindex:

   MOSAiCS \(MOdel\-based one and two Sample Analysis and Inference for ChIP\-Seq\)

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/mosaics.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-mosaics <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mosaics>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mosaics/meta.yaml>`_
   :links: biotools: :biotools:`mosaics`, doi: :doi:`10.1198/jasa.2011.ap09706`

   This package provides functions for fitting MOSAiCS and MOSAiCS\-HMM\, a statistical framework to analyze one\-sample or two\-sample ChIP\-seq data of transcription factor binding and histone modification.


.. conda:package:: bioconductor-mosaics

   |downloads_bioconductor-mosaics| |docker_bioconductor-mosaics|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>2.28.0-0</code>,  <code>2.26.0-0</code>,  <code>2.24.0-0</code>,  <code>2.22.0-1</code>,  <code>2.20.0-0</code>,  <code>2.18.0-0</code>,  <code>2.16.0-0</code>,  <code>2.14.0-0</code>,  <code>2.10.0-0</code>,  </span></summary>
      

      ``2.28.0-0``,  ``2.26.0-0``,  ``2.24.0-0``,  ``2.22.0-1``,  ``2.20.0-0``,  ``2.18.0-0``,  ``2.16.0-0``,  ``2.14.0-0``,  ``2.10.0-0``,  ``2.4.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=7.5.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=7.5.0``
   :depends perl: ``>=5.30.3,<5.30.4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-lattice: 
   :depends r-mass: 
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mosaics

   and update with::

      conda update bioconductor-mosaics

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mosaics:<tag>

   (see `bioconductor-mosaics/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mosaics| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mosaics.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mosaics
   :alt:   (downloads)
.. |docker_bioconductor-mosaics| image:: https://quay.io/repository/biocontainers/bioconductor-mosaics/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mosaics
.. _`bioconductor-mosaics/tags`: https://quay.io/repository/biocontainers/bioconductor-mosaics?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mosaics/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mosaics/README.html