:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-meshr'
.. highlight: bash

bioconductor-meshr
==================

.. conda:recipe:: bioconductor-meshr
   :replaces_section_title:
   :noindex:

   Tools for conducting enrichment analysis of MeSH

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/meshr.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-meshr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-meshr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-meshr/meta.yaml>`_

   A set of annotation maps describing the entire MeSH assembled using data from MeSH.


.. conda:package:: bioconductor-meshr

   |downloads_bioconductor-meshr| |docker_bioconductor-meshr|

   :versions:
      
      

      ``1.26.0-0``,  ``1.24.1-0``,  ``1.22.0-0``,  ``1.20.0-1``,  ``1.18.0-1``,  ``1.18.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-category: ``>=2.56.0,<2.57.0``
   :depends bioconductor-cummerbund: ``>=2.32.0,<2.33.0``
   :depends bioconductor-mesh.aca.eg.db: ``>=1.13.0,<1.14.0``
   :depends bioconductor-mesh.aor.db: ``>=1.13.0,<1.14.0``
   :depends bioconductor-mesh.bsu.168.eg.db: ``>=1.13.0,<1.14.0``
   :depends bioconductor-mesh.db: ``>=1.13.0,<1.14.0``
   :depends bioconductor-mesh.hsa.eg.db: ``>=1.13.0,<1.14.0``
   :depends bioconductor-mesh.pcr.db: ``>=1.13.0,<1.14.0``
   :depends bioconductor-mesh.syn.eg.db: ``>=1.13.0,<1.14.0``
   :depends bioconductor-meshdbi: ``>=1.26.0,<1.27.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-fdrtool: 
   :depends r-rsqlite: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-meshr

   and update with::

      conda update bioconductor-meshr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-meshr:<tag>

   (see `bioconductor-meshr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-meshr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-meshr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-meshr
   :alt:   (downloads)
.. |docker_bioconductor-meshr| image:: https://quay.io/repository/biocontainers/bioconductor-meshr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-meshr
.. _`bioconductor-meshr/tags`: https://quay.io/repository/biocontainers/bioconductor-meshr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-meshr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-meshr/README.html