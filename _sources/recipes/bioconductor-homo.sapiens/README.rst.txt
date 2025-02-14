:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-homo.sapiens'
.. highlight: bash

bioconductor-homo.sapiens
=========================

.. conda:recipe:: bioconductor-homo.sapiens
   :replaces_section_title:
   :noindex:

   Annotation package for the Homo.sapiens object

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/Homo.sapiens.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-homo.sapiens <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-homo.sapiens>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-homo.sapiens/meta.yaml>`_

   Contains the Homo.sapiens object to access data from several related annotation packages.


.. conda:package:: bioconductor-homo.sapiens

   |downloads_bioconductor-homo.sapiens| |docker_bioconductor-homo.sapiens|

   :versions:
      
      

      ``1.3.1-10``,  ``1.3.1-9``,  ``1.3.1-8``,  ``1.3.1-7``,  ``1.3.1-6``,  ``1.3.1-4``,  ``1.3.1-3``,  ``1.3.1-1``,  ``1.3.1-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-go.db: ``>=3.12.1,<3.13.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends bioconductor-organismdbi: ``>=1.32.0,<1.33.0``
   :depends bioconductor-txdb.hsapiens.ucsc.hg19.knowngene: ``>=3.2.0,<3.3.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-homo.sapiens

   and update with::

      conda update bioconductor-homo.sapiens

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-homo.sapiens:<tag>

   (see `bioconductor-homo.sapiens/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-homo.sapiens| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-homo.sapiens.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-homo.sapiens
   :alt:   (downloads)
.. |docker_bioconductor-homo.sapiens| image:: https://quay.io/repository/biocontainers/bioconductor-homo.sapiens/status
   :target: https://quay.io/repository/biocontainers/bioconductor-homo.sapiens
.. _`bioconductor-homo.sapiens/tags`: https://quay.io/repository/biocontainers/bioconductor-homo.sapiens?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-homo.sapiens/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-homo.sapiens/README.html