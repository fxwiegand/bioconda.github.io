:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-greengenes13.5mgdb'
.. highlight: bash

bioconductor-greengenes13.5mgdb
===============================

.. conda:recipe:: bioconductor-greengenes13.5mgdb
   :replaces_section_title:
   :noindex:

   Greengenes 13.5 16S rRNA Database Annotation Data

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/greengenes13.5MgDb.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-greengenes13.5mgdb <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-greengenes13.5mgdb>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-greengenes13.5mgdb/meta.yaml>`_

   Metagenome annotation package with for the Greengenes 16S rRNA Database version 13.5. Contains a MgDb\-class object\, defined in the metagenomeFeatures package.


.. conda:package:: bioconductor-greengenes13.5mgdb

   |downloads_bioconductor-greengenes13.5mgdb| |docker_bioconductor-greengenes13.5mgdb|

   :versions:
      
      

      ``2.0.0-6``,  ``2.0.0-5``,  ``2.0.0-4``,  ``2.0.0-3``,  ``2.0.0-2``,  ``2.0.0-0``

      

   
   :depends bioconductor-metagenomefeatures: ``>=2.10.0,<2.11.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-greengenes13.5mgdb

   and update with::

      conda update bioconductor-greengenes13.5mgdb

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-greengenes13.5mgdb:<tag>

   (see `bioconductor-greengenes13.5mgdb/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-greengenes13.5mgdb| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-greengenes13.5mgdb.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-greengenes13.5mgdb
   :alt:   (downloads)
.. |docker_bioconductor-greengenes13.5mgdb| image:: https://quay.io/repository/biocontainers/bioconductor-greengenes13.5mgdb/status
   :target: https://quay.io/repository/biocontainers/bioconductor-greengenes13.5mgdb
.. _`bioconductor-greengenes13.5mgdb/tags`: https://quay.io/repository/biocontainers/bioconductor-greengenes13.5mgdb?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-greengenes13.5mgdb/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-greengenes13.5mgdb/README.html