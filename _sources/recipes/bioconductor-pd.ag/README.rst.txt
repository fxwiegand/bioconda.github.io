:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-pd.ag'
.. highlight: bash

bioconductor-pd.ag
==================

.. conda:recipe:: bioconductor-pd.ag
   :replaces_section_title:
   :noindex:

   Platform Design Info for The Manufacturer\'s Name AG

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/pd.ag.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-pd.ag <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.ag>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-pd.ag/meta.yaml>`_

   Platform Design Info for The Manufacturer\'s Name AG


.. conda:package:: bioconductor-pd.ag

   |downloads_bioconductor-pd.ag| |docker_bioconductor-pd.ag|

   :versions:
      
      

      ``3.12.0-6``,  ``3.12.0-5``,  ``3.12.0-4``,  ``3.12.0-3``,  ``3.12.0-2``,  ``3.12.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-oligo: ``>=1.54.0,<1.55.0``
   :depends bioconductor-oligoclasses: ``>=1.52.0,<1.53.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dbi: ``>=0.3.1``
   :depends r-rsqlite: ``>=1.0.0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-pd.ag

   and update with::

      conda update bioconductor-pd.ag

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-pd.ag:<tag>

   (see `bioconductor-pd.ag/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-pd.ag| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-pd.ag.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-pd.ag
   :alt:   (downloads)
.. |docker_bioconductor-pd.ag| image:: https://quay.io/repository/biocontainers/bioconductor-pd.ag/status
   :target: https://quay.io/repository/biocontainers/bioconductor-pd.ag
.. _`bioconductor-pd.ag/tags`: https://quay.io/repository/biocontainers/bioconductor-pd.ag?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-pd.ag/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-pd.ag/README.html