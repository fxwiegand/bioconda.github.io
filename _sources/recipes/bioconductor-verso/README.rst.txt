:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-verso'
.. highlight: bash

bioconductor-verso
==================

.. conda:recipe:: bioconductor-verso
   :replaces_section_title:
   :noindex:

   Viral Evolution ReconStructiOn \(VERSO\)

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/VERSO.html
   :license: file LICENSE
   :recipe: /`bioconductor-verso <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-verso>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-verso/meta.yaml>`_

   Mutations that rapidly accumulate in viral genomes during a pandemic can be used to track the evolution of the virus and\, accordingly\, unravel the viral infection network. To this extent\, sequencing samples of the virus can be employed to estimate models from genomic epidemiology and may serve\, for instance\, to estimate the proportion of undetected infected people by uncovering cryptic transmissions\, as well as to predict likely trends in the number of infected\, hospitalized\, dead and recovered people. VERSO is an algorithmic framework that processes variants profiles from viral samples to produce phylogenetic models of viral evolution. The approach solves a Boolean Matrix Factorization problem with phylogenetic constraints\, by maximizing a log\-likelihood function. VERSO includes two separate and subsequent steps\; in this package we provide an R implementation of VERSO STEP 1.


.. conda:package:: bioconductor-verso

   |downloads_bioconductor-verso| |docker_bioconductor-verso|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends r-ape: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-rfast: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-verso

   and update with::

      conda update bioconductor-verso

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-verso:<tag>

   (see `bioconductor-verso/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-verso| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-verso.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-verso
   :alt:   (downloads)
.. |docker_bioconductor-verso| image:: https://quay.io/repository/biocontainers/bioconductor-verso/status
   :target: https://quay.io/repository/biocontainers/bioconductor-verso
.. _`bioconductor-verso/tags`: https://quay.io/repository/biocontainers/bioconductor-verso?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-verso/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-verso/README.html