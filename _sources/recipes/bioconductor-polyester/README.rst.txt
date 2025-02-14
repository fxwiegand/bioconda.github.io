:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-polyester'
.. highlight: bash

bioconductor-polyester
======================

.. conda:recipe:: bioconductor-polyester
   :replaces_section_title:
   :noindex:

   Simulate RNA\-seq reads

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/polyester.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-polyester <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-polyester>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-polyester/meta.yaml>`_

   This package can be used to simulate RNA\-seq reads from differential expression experiments with replicates. The reads can then be aligned and used to perform comparisons of methods for differential expression.


.. conda:package:: bioconductor-polyester

   |downloads_bioconductor-polyester| |docker_bioconductor-polyester|

   :versions:
      
      

      ``1.26.0-1``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-1``,  ``1.18.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-zlibbioc: ``>=1.36.0,<1.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-logspline: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-polyester

   and update with::

      conda update bioconductor-polyester

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-polyester:<tag>

   (see `bioconductor-polyester/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-polyester| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-polyester.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-polyester
   :alt:   (downloads)
.. |docker_bioconductor-polyester| image:: https://quay.io/repository/biocontainers/bioconductor-polyester/status
   :target: https://quay.io/repository/biocontainers/bioconductor-polyester
.. _`bioconductor-polyester/tags`: https://quay.io/repository/biocontainers/bioconductor-polyester?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-polyester/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-polyester/README.html