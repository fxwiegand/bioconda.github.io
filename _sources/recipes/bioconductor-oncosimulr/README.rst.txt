:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-oncosimulr'
.. highlight: bash

bioconductor-oncosimulr
=======================

.. conda:recipe:: bioconductor-oncosimulr
   :replaces_section_title:
   :noindex:

   Forward Genetic Simulation of Cancer Progression with Epistasis

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/OncoSimulR.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-oncosimulr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-oncosimulr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-oncosimulr/meta.yaml>`_
   :links: biotools: :biotools:`oncosimulr`

   Functions for forward population genetic simulation in asexual populations\, with special focus on cancer progression. Fitness can be an arbitrary function of genetic interactions between multiple genes or modules of genes\, including epistasis\, order restrictions in mutation accumulation\, and order effects.  Mutation rates can differ between genes\, and we can include mutator\/antimutator genes \(to model mutator phenotypes\). Simulations use continuous\-time models and can include driver and passenger genes and modules.  Also included are functions for\: simulating random DAGs of the type found in Oncogenetic Trees\, Conjunctive Bayesian Networks\, and other cancer progression models\; plotting and sampling from single or multiple realizations of the simulations\, including single\-cell sampling\; plotting the parent\-child relationships of the clones\; generating random fitness landscapes \(from Rough Mount Fuji\, House of Cards\, additive\, NK\, Ising\, and Eggbox models\) and plotting them.


.. conda:package:: bioconductor-oncosimulr

   |downloads_bioconductor-oncosimulr| |docker_bioconductor-oncosimulr|

   :versions:
      
      

      ``2.20.0-1``,  ``2.20.0-0``,  ``2.18.0-0``,  ``2.16.0-0``,  ``2.14.0-1``,  ``2.12.0-0``,  ``2.10.0-0``,  ``2.8.0-0``

      

   
   :depends bioconductor-graph: ``>=1.68.0,<1.69.0``
   :depends bioconductor-rgraphviz: ``>=2.34.0,<2.35.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-car: 
   :depends r-data.table: 
   :depends r-dplyr: 
   :depends r-ggplot2: 
   :depends r-ggrepel: 
   :depends r-gtools: 
   :depends r-igraph: 
   :depends r-rcolorbrewer: 
   :depends r-rcpp: ``>=0.12.4``
   :depends r-smatr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-oncosimulr

   and update with::

      conda update bioconductor-oncosimulr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-oncosimulr:<tag>

   (see `bioconductor-oncosimulr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-oncosimulr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-oncosimulr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-oncosimulr
   :alt:   (downloads)
.. |docker_bioconductor-oncosimulr| image:: https://quay.io/repository/biocontainers/bioconductor-oncosimulr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-oncosimulr
.. _`bioconductor-oncosimulr/tags`: https://quay.io/repository/biocontainers/bioconductor-oncosimulr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-oncosimulr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-oncosimulr/README.html