:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-somaticadata'
.. highlight: bash

bioconductor-somaticadata
=========================

.. conda:recipe:: bioconductor-somaticadata
   :replaces_section_title:
   :noindex:

   An example cancer whole genome sequencing data for the SomatiCA package

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/SomatiCAData.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-somaticadata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-somaticadata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-somaticadata/meta.yaml>`_

   An example cancer whole genome sequencing data for the SomatiCA package


.. conda:package:: bioconductor-somaticadata

   |downloads_bioconductor-somaticadata| |docker_bioconductor-somaticadata|

   :versions:
      
      

      ``1.28.0-1``,  ``1.28.0-0``,  ``1.27.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.22.0-0``,  ``1.20.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-somaticadata

   and update with::

      conda update bioconductor-somaticadata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-somaticadata:<tag>

   (see `bioconductor-somaticadata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-somaticadata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-somaticadata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-somaticadata
   :alt:   (downloads)
.. |docker_bioconductor-somaticadata| image:: https://quay.io/repository/biocontainers/bioconductor-somaticadata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-somaticadata
.. _`bioconductor-somaticadata/tags`: https://quay.io/repository/biocontainers/bioconductor-somaticadata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-somaticadata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-somaticadata/README.html