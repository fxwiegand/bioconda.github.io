:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-interactionset'
.. highlight: bash

bioconductor-interactionset
===========================

.. conda:recipe:: bioconductor-interactionset
   :replaces_section_title:
   :noindex:

   Base Classes for Storing Genomic Interaction Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/InteractionSet.html
   :license: GPL-3
   :recipe: /`bioconductor-interactionset <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-interactionset>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-interactionset/meta.yaml>`_
   :links: biotools: :biotools:`interactionset`

   Provides the GInteractions\, InteractionSet and ContactMatrix objects and associated methods for storing and manipulating genomic interaction data from Hi\-C and ChIA\-PET experiments.


.. conda:package:: bioconductor-interactionset

   |downloads_bioconductor-interactionset| |docker_bioconductor-interactionset|

   :versions:
      
      

      ``1.18.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-matrix: 
   :depends r-rcpp: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-interactionset

   and update with::

      conda update bioconductor-interactionset

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-interactionset:<tag>

   (see `bioconductor-interactionset/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-interactionset| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-interactionset.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-interactionset
   :alt:   (downloads)
.. |docker_bioconductor-interactionset| image:: https://quay.io/repository/biocontainers/bioconductor-interactionset/status
   :target: https://quay.io/repository/biocontainers/bioconductor-interactionset
.. _`bioconductor-interactionset/tags`: https://quay.io/repository/biocontainers/bioconductor-interactionset?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-interactionset/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-interactionset/README.html