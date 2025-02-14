:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-missrows'
.. highlight: bash

bioconductor-missrows
=====================

.. conda:recipe:: bioconductor-missrows
   :replaces_section_title:
   :noindex:

   Handling Missing Individuals in Multi\-Omics Data Integration

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/missRows.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-missrows <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-missrows>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-missrows/meta.yaml>`_

   The missRows package implements the MI\-MFA method to deal with missing individuals \(\'biological units\'\) in multi\-omics data integration. The MI\-MFA method generates multiple imputed datasets from a Multiple Factor Analysis model\, then the yield results are combined in a single consensus solution. The package provides functions for estimating coordinates of individuals and variables\, imputing missing individuals\, and various diagnostic plots to inspect the pattern of missingness and visualize the uncertainty due to missing values.


.. conda:package:: bioconductor-missrows

   |downloads_bioconductor-missrows| |docker_bioconductor-missrows|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.2.0-0``

      

   
   :depends bioconductor-multiassayexperiment: ``>=1.16.0,<1.17.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-gtools: 
   :depends r-plyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-missrows

   and update with::

      conda update bioconductor-missrows

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-missrows:<tag>

   (see `bioconductor-missrows/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-missrows| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-missrows.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-missrows
   :alt:   (downloads)
.. |docker_bioconductor-missrows| image:: https://quay.io/repository/biocontainers/bioconductor-missrows/status
   :target: https://quay.io/repository/biocontainers/bioconductor-missrows
.. _`bioconductor-missrows/tags`: https://quay.io/repository/biocontainers/bioconductor-missrows?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-missrows/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-missrows/README.html