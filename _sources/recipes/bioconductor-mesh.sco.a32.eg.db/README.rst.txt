:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mesh.sco.a32.eg.db'
.. highlight: bash

bioconductor-mesh.sco.a32.eg.db
===============================

.. conda:recipe:: bioconductor-mesh.sco.a32.eg.db
   :replaces_section_title:
   :noindex:

   Mapping table for Streptomyces coelicolor A3\(2\) Gene ID to MeSH

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/MeSH.Sco.A32.eg.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-mesh.sco.a32.eg.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mesh.sco.a32.eg.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mesh.sco.a32.eg.db/meta.yaml>`_

   Entrez Gene ID to MeSH ID table.


.. conda:package:: bioconductor-mesh.sco.a32.eg.db

   |downloads_bioconductor-mesh.sco.a32.eg.db| |docker_bioconductor-mesh.sco.a32.eg.db|

   :versions:
      
      

      ``1.13.0-3``,  ``1.13.0-2``,  ``1.13.0-1``,  ``1.13.0-0``,  ``1.12.0-1``,  ``1.11.0-1``,  ``1.11.0-0``

      

   
   :depends bioconductor-meshdbi: ``>=1.26.0,<1.27.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mesh.sco.a32.eg.db

   and update with::

      conda update bioconductor-mesh.sco.a32.eg.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mesh.sco.a32.eg.db:<tag>

   (see `bioconductor-mesh.sco.a32.eg.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mesh.sco.a32.eg.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mesh.sco.a32.eg.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mesh.sco.a32.eg.db
   :alt:   (downloads)
.. |docker_bioconductor-mesh.sco.a32.eg.db| image:: https://quay.io/repository/biocontainers/bioconductor-mesh.sco.a32.eg.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mesh.sco.a32.eg.db
.. _`bioconductor-mesh.sco.a32.eg.db/tags`: https://quay.io/repository/biocontainers/bioconductor-mesh.sco.a32.eg.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mesh.sco.a32.eg.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mesh.sco.a32.eg.db/README.html