:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pviz'
.. highlight: bash

bioconductor-pviz
=================

.. conda:recipe:: bioconductor-pviz
   :replaces_section_title:
   :noindex:

   Peptide Annotation and Data Visualization using Gviz

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/Pviz.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-pviz <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pviz>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pviz/meta.yaml>`_
   :links: biotools: :biotools:`pviz`, doi: :doi:`10.1007/978-1-4939-3037-1_10`

   Pviz adapts the Gviz package for protein sequences and data.


.. conda:package:: bioconductor-pviz

   |downloads_bioconductor-pviz| |docker_bioconductor-pviz|

   :versions:
      
      

      ``1.24.0-1``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-biovizbase: ``>=1.38.0,<1.39.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-gviz: ``>=1.34.0,<1.35.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pviz

   and update with::

      conda update bioconductor-pviz

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pviz:<tag>

   (see `bioconductor-pviz/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pviz| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pviz.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pviz
   :alt:   (downloads)
.. |docker_bioconductor-pviz| image:: https://quay.io/repository/biocontainers/bioconductor-pviz/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pviz
.. _`bioconductor-pviz/tags`: https://quay.io/repository/biocontainers/bioconductor-pviz?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pviz/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pviz/README.html