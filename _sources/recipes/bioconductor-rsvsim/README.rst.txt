:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rsvsim'
.. highlight: bash

bioconductor-rsvsim
===================

.. conda:recipe:: bioconductor-rsvsim
   :replaces_section_title:
   :noindex:

   RSVSim\: an R\/Bioconductor package for the simulation of structural variations

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/RSVSim.html
   :license: LGPL-3
   :recipe: /`bioconductor-rsvsim <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rsvsim>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rsvsim/meta.yaml>`_
   :links: biotools: :biotools:`rsvsim`, doi: :doi:`10.1093/bioinformatics/btt198`

   RSVSim is a package for the simulation of deletions\, insertions\, inversion\, tandem\-duplications and translocations of various sizes in any genome available as FASTA\-file or BSgenome data package. SV breakpoints can be placed uniformly accross the whole genome\, with a bias towards repeat regions and regions of high homology \(for hg19\) or at user\-supplied coordinates.


.. conda:package:: bioconductor-rsvsim

   |downloads_bioconductor-rsvsim| |docker_bioconductor-rsvsim|

   :versions:
      
      

      ``1.30.0-1``,  ``1.30.0-0``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-1``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-shortread: ``>=1.48.0,<1.49.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rsvsim

   and update with::

      conda update bioconductor-rsvsim

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rsvsim:<tag>

   (see `bioconductor-rsvsim/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rsvsim| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rsvsim.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rsvsim
   :alt:   (downloads)
.. |docker_bioconductor-rsvsim| image:: https://quay.io/repository/biocontainers/bioconductor-rsvsim/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rsvsim
.. _`bioconductor-rsvsim/tags`: https://quay.io/repository/biocontainers/bioconductor-rsvsim?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rsvsim/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rsvsim/README.html