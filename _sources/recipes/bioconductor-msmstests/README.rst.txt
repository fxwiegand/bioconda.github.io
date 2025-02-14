:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-msmstests'
.. highlight: bash

bioconductor-msmstests
======================

.. conda:recipe:: bioconductor-msmstests
   :replaces_section_title:
   :noindex:

   LC\-MS\/MS Differential Expression Tests

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/msmsTests.html
   :license: GPL-2
   :recipe: /`bioconductor-msmstests <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msmstests>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-msmstests/meta.yaml>`_

   Statistical tests for label\-free LC\-MS\/MS data by spectral counts\, to discover differentially expressed proteins between two biological conditions. Three tests are available\: Poisson GLM regression\, quasi\-likelihood GLM regression\, and the negative binomial of the edgeR package.The three models admit blocking factors to control for nuissance variables.To assure a good level of reproducibility a post\-test filter is available\, where we may set the minimum effect size considered biologicaly relevant\, and the minimum expression of the most abundant condition.


.. conda:package:: bioconductor-msmstests

   |downloads_bioconductor-msmstests| |docker_bioconductor-msmstests|

   :versions:
      
      

      ``1.28.0-1``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.20.1-0``

      

   
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-msmseda: ``>=1.28.0,<1.29.0``
   :depends bioconductor-msnbase: ``>=2.16.0,<2.17.0``
   :depends bioconductor-qvalue: ``>=2.22.0,<2.23.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-msmstests

   and update with::

      conda update bioconductor-msmstests

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-msmstests:<tag>

   (see `bioconductor-msmstests/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-msmstests| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-msmstests.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-msmstests
   :alt:   (downloads)
.. |docker_bioconductor-msmstests| image:: https://quay.io/repository/biocontainers/bioconductor-msmstests/status
   :target: https://quay.io/repository/biocontainers/bioconductor-msmstests
.. _`bioconductor-msmstests/tags`: https://quay.io/repository/biocontainers/bioconductor-msmstests?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-msmstests/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-msmstests/README.html