:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-genomicalignments'
.. highlight: bash

bioconductor-genomicalignments
==============================

.. conda:recipe:: bioconductor-genomicalignments
   :replaces_section_title:
   :noindex:

   Representation and manipulation of short genomic alignments

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/GenomicAlignments.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-genomicalignments <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomicalignments>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-genomicalignments/meta.yaml>`_
   :links: biotools: :biotools:`genomicalignments`

   Provides efficient containers for storing and manipulating short genomic alignments \(typically obtained by aligning short reads to a reference genome\). This includes read counting\, computing the coverage\, junction detection\, and working with the nucleotide content of the alignments.


.. conda:package:: bioconductor-genomicalignments

   |downloads_bioconductor-genomicalignments| |docker_bioconductor-genomicalignments|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.26.0-1</code>,  <code>1.26.0-0</code>,  <code>1.24.0-0</code>,  <code>1.22.0-0</code>,  <code>1.20.1-0</code>,  <code>1.20.0-0</code>,  <code>1.18.1-0</code>,  <code>1.18.0-0</code>,  <code>1.16.0-0</code>,  </span></summary>
      

      ``1.26.0-1``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.1-0``,  ``1.20.0-0``,  ``1.18.1-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.1-0``,  ``1.14.0-0``,  ``1.12.2-0``,  ``1.10.0-0``,  ``1.8.4-0``,  ``1.6.3-1``,  ``1.6.3-0``,  ``1.6.1-0``,  ``1.6.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-genomicalignments

   and update with::

      conda update bioconductor-genomicalignments

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-genomicalignments:<tag>

   (see `bioconductor-genomicalignments/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-genomicalignments| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-genomicalignments.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-genomicalignments
   :alt:   (downloads)
.. |docker_bioconductor-genomicalignments| image:: https://quay.io/repository/biocontainers/bioconductor-genomicalignments/status
   :target: https://quay.io/repository/biocontainers/bioconductor-genomicalignments
.. _`bioconductor-genomicalignments/tags`: https://quay.io/repository/biocontainers/bioconductor-genomicalignments?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-genomicalignments/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-genomicalignments/README.html