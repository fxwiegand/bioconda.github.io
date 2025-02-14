:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bayseq'
.. highlight: bash

bioconductor-bayseq
===================

.. conda:recipe:: bioconductor-bayseq
   :replaces_section_title:
   :noindex:

   Empirical Bayesian analysis of patterns of differential expression in count data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/baySeq.html
   :license: GPL-3
   :recipe: /`bioconductor-bayseq <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bayseq>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bayseq/meta.yaml>`_
   :links: biotools: :biotools:`bayseq`, doi: :doi:`10.1186/1471-2105-11-422`

   This package identifies differential expression in high\-throughput \'count\' data\, such as that derived from next\-generation sequencing machines\, calculating estimated posterior likelihoods of differential expression \(or more complex hypotheses\) via empirical Bayesian methods.


.. conda:package:: bioconductor-bayseq

   |downloads_bioconductor-bayseq| |docker_bioconductor-bayseq|

   :versions:
      
      

      ``2.24.0-1``,  ``2.24.0-0``,  ``2.22.0-0``,  ``2.20.0-0``,  ``2.18.0-1``,  ``2.16.0-0``,  ``2.14.0-0``,  ``2.12.0-0``,  ``2.10.0-0``

      

   
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends r-abind: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bayseq

   and update with::

      conda update bioconductor-bayseq

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bayseq:<tag>

   (see `bioconductor-bayseq/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bayseq| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bayseq.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bayseq
   :alt:   (downloads)
.. |docker_bioconductor-bayseq| image:: https://quay.io/repository/biocontainers/bioconductor-bayseq/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bayseq
.. _`bioconductor-bayseq/tags`: https://quay.io/repository/biocontainers/bioconductor-bayseq?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bayseq/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bayseq/README.html