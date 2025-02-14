:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-calm'
.. highlight: bash

bioconductor-calm
=================

.. conda:recipe:: bioconductor-calm
   :replaces_section_title:
   :noindex:

   Covariate Assisted Large\-scale Multiple testing

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/calm.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-calm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-calm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-calm/meta.yaml>`_

   Statistical methods for multiple testing with covariate information. Traditional multiple testing methods only consider a list of test statistics\, such as p\-values. Our methods incorporate the auxiliary information\, such as the lengths of gene coding regions or the minor allele frequencies of SNPs\, to improve power.


.. conda:package:: bioconductor-calm

   |downloads_bioconductor-calm| |docker_bioconductor-calm|

   :versions:
      
      

      ``1.4.0-1``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-mgcv: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-calm

   and update with::

      conda update bioconductor-calm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-calm:<tag>

   (see `bioconductor-calm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-calm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-calm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-calm
   :alt:   (downloads)
.. |docker_bioconductor-calm| image:: https://quay.io/repository/biocontainers/bioconductor-calm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-calm
.. _`bioconductor-calm/tags`: https://quay.io/repository/biocontainers/bioconductor-calm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-calm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-calm/README.html