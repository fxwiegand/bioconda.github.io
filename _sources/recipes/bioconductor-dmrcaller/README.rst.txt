:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-dmrcaller'
.. highlight: bash

bioconductor-dmrcaller
======================

.. conda:recipe:: bioconductor-dmrcaller
   :replaces_section_title:
   :noindex:

   Differentially Methylated Regions caller

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/DMRcaller.html
   :license: GPL-3
   :recipe: /`bioconductor-dmrcaller <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrcaller>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrcaller/meta.yaml>`_

   Uses Bisulfite sequencing data in two conditions and identifies differentially methylated regions between the conditions in CG and non\-CG context. The input is the CX report files produced by Bismark and the output is a list of DMRs stored as GRanges objects.


.. conda:package:: bioconductor-dmrcaller

   |downloads_bioconductor-dmrcaller| |docker_bioconductor-dmrcaller|

   :versions:
      
      

      ``1.22.0-1``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-1``,  ``1.14.0-0``

      

   
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-betareg: 
   :depends r-rcpp: 
   :depends r-rcpproll: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-dmrcaller

   and update with::

      conda update bioconductor-dmrcaller

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-dmrcaller:<tag>

   (see `bioconductor-dmrcaller/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-dmrcaller| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-dmrcaller.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-dmrcaller
   :alt:   (downloads)
.. |docker_bioconductor-dmrcaller| image:: https://quay.io/repository/biocontainers/bioconductor-dmrcaller/status
   :target: https://quay.io/repository/biocontainers/bioconductor-dmrcaller
.. _`bioconductor-dmrcaller/tags`: https://quay.io/repository/biocontainers/bioconductor-dmrcaller?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-dmrcaller/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-dmrcaller/README.html