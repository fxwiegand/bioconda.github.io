:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mirnatap.db'
.. highlight: bash

bioconductor-mirnatap.db
========================

.. conda:recipe:: bioconductor-mirnatap.db
   :replaces_section_title:
   :noindex:

   Data for miRNAtap

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/miRNAtap.db.html
   :license: GPL-2
   :recipe: /`bioconductor-mirnatap.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mirnatap.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mirnatap.db/meta.yaml>`_

   This package holds the database for miRNAtap.


.. conda:package:: bioconductor-mirnatap.db

   |downloads_bioconductor-mirnatap.db| |docker_bioconductor-mirnatap.db|

   :versions:
      
      

      ``0.99.10-9``,  ``0.99.10-8``,  ``0.99.10-7``,  ``0.99.10-6``,  ``0.99.10-5``,  ``0.99.10-3``,  ``0.99.10-2``,  ``0.99.10-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-mirnatap: ``>=1.23.0,<1.24.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dbi: 
   :depends r-rsqlite: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mirnatap.db

   and update with::

      conda update bioconductor-mirnatap.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mirnatap.db:<tag>

   (see `bioconductor-mirnatap.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mirnatap.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mirnatap.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mirnatap.db
   :alt:   (downloads)
.. |docker_bioconductor-mirnatap.db| image:: https://quay.io/repository/biocontainers/bioconductor-mirnatap.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mirnatap.db
.. _`bioconductor-mirnatap.db/tags`: https://quay.io/repository/biocontainers/bioconductor-mirnatap.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mirnatap.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mirnatap.db/README.html