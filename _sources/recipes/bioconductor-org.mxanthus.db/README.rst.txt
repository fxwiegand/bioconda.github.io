:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-org.mxanthus.db'
.. highlight: bash

bioconductor-org.mxanthus.db
============================

.. conda:recipe:: bioconductor-org.mxanthus.db
   :replaces_section_title:
   :noindex:

   Genome wide annotation for Myxococcus xanthus DK 1622

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/org.Mxanthus.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-org.mxanthus.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-org.mxanthus.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-org.mxanthus.db/meta.yaml>`_

   Genome wide annotation for Myxococcus xanthus DK 1622\, primarily based on mapping using Gene identifiers.


.. conda:package:: bioconductor-org.mxanthus.db

   |downloads_bioconductor-org.mxanthus.db| |docker_bioconductor-org.mxanthus.db|

   :versions:
      
      

      ``1.0.27-2``,  ``1.0.27-1``,  ``1.0.27-0``,  ``1.0.23-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-annotationhub: ``>=2.22.0,<2.23.0``
   :depends bioconductor-biocfilecache: ``>=1.14.0,<1.15.0``
   :depends bioconductor-biocstyle: ``>=2.18.0,<2.19.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-org.mxanthus.db

   and update with::

      conda update bioconductor-org.mxanthus.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-org.mxanthus.db:<tag>

   (see `bioconductor-org.mxanthus.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-org.mxanthus.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-org.mxanthus.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-org.mxanthus.db
   :alt:   (downloads)
.. |docker_bioconductor-org.mxanthus.db| image:: https://quay.io/repository/biocontainers/bioconductor-org.mxanthus.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-org.mxanthus.db
.. _`bioconductor-org.mxanthus.db/tags`: https://quay.io/repository/biocontainers/bioconductor-org.mxanthus.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-org.mxanthus.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-org.mxanthus.db/README.html