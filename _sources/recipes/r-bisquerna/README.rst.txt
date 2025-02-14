:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-bisquerna'
.. highlight: bash

r-bisquerna
===========

.. conda:recipe:: r-bisquerna
   :replaces_section_title:
   :noindex:

   Provides tools to accurately estimate cell type abundances from heterogeneous bulk expression.

   :homepage: https://www.biorxiv.org/content/10.1101/669911v1
   :license: GPL3 / GPL-3.0-only
   :recipe: /`r-bisquerna <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-bisquerna>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-bisquerna/meta.yaml>`_

   A reference\-based method utilizes single\-cell information to generate a signature matrix and transformation of bulk expression for accurate regression based estimates. A marker\-based method utilizes known cell\-specific marker genes to measure relative abundances across samples. For more details\, see Jew and Alvarez et al \(2019\) \<doi\:10.1101\/669911\>.


.. conda:package:: r-bisquerna

   |downloads_r-bisquerna| |docker_r-bisquerna|

   :versions:
      
      

      ``1.0.4-1``,  ``1.0.4-0``,  ``1.0.3-1``,  ``1.0.3-0``,  ``1.0.2-0``,  ``1.0.1-0``,  ``1.0-1``,  ``1.0-0``

      

   
   :depends bioconductor-biobase: 
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-limsolve: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-bisquerna

   and update with::

      conda update r-bisquerna

   or use the docker container::

      docker pull quay.io/biocontainers/r-bisquerna:<tag>

   (see `r-bisquerna/tags`_ for valid values for ``<tag>``)


.. |downloads_r-bisquerna| image:: https://img.shields.io/conda/dn/bioconda/r-bisquerna.svg?style=flat
   :target: https://anaconda.org/bioconda/r-bisquerna
   :alt:   (downloads)
.. |docker_r-bisquerna| image:: https://quay.io/repository/biocontainers/r-bisquerna/status
   :target: https://quay.io/repository/biocontainers/r-bisquerna
.. _`r-bisquerna/tags`: https://quay.io/repository/biocontainers/r-bisquerna?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-bisquerna/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-bisquerna/README.html