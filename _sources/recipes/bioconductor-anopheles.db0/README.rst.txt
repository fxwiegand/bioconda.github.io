:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-anopheles.db0'
.. highlight: bash

bioconductor-anopheles.db0
==========================

.. conda:recipe:: bioconductor-anopheles.db0
   :replaces_section_title:
   :noindex:

   Base Level Annotation databases for anopheles

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/anopheles.db0.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-anopheles.db0 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-anopheles.db0>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-anopheles.db0/meta.yaml>`_

   Base annotation databases for anopheles\, intended ONLY to be used by AnnotationDbi to produce regular annotation packages.


.. conda:package:: bioconductor-anopheles.db0

   |downloads_bioconductor-anopheles.db0| |docker_bioconductor-anopheles.db0|

   :versions:
      
      

      ``3.12.0-1``,  ``3.12.0-0``,  ``3.11.2-0``,  ``3.10.0-0``,  ``3.8.2-1``,  ``3.7.1-1``,  ``3.7.1-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-anopheles.db0

   and update with::

      conda update bioconductor-anopheles.db0

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-anopheles.db0:<tag>

   (see `bioconductor-anopheles.db0/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-anopheles.db0| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-anopheles.db0.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-anopheles.db0
   :alt:   (downloads)
.. |docker_bioconductor-anopheles.db0| image:: https://quay.io/repository/biocontainers/bioconductor-anopheles.db0/status
   :target: https://quay.io/repository/biocontainers/bioconductor-anopheles.db0
.. _`bioconductor-anopheles.db0/tags`: https://quay.io/repository/biocontainers/bioconductor-anopheles.db0?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-anopheles.db0/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-anopheles.db0/README.html