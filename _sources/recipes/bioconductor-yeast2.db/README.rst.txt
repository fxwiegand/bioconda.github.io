:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-yeast2.db'
.. highlight: bash

bioconductor-yeast2.db
======================

.. conda:recipe:: bioconductor-yeast2.db
   :replaces_section_title:
   :noindex:

   Affymetrix Yeast Genome 2.0 Array annotation data \(chip yeast2\)

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/yeast2.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-yeast2.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yeast2.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-yeast2.db/meta.yaml>`_

   Affymetrix Yeast Genome 2.0 Array annotation data \(chip yeast2\) assembled using data from public repositories


.. conda:package:: bioconductor-yeast2.db

   |downloads_bioconductor-yeast2.db| |docker_bioconductor-yeast2.db|

   :versions:
      
      

      ``3.2.3-6``,  ``3.2.3-5``,  ``3.2.3-4``,  ``3.2.3-3``,  ``3.2.3-2``,  ``3.2.3-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-org.sc.sgd.db: ``>=3.12.0,<3.13.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-yeast2.db

   and update with::

      conda update bioconductor-yeast2.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-yeast2.db:<tag>

   (see `bioconductor-yeast2.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-yeast2.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-yeast2.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-yeast2.db
   :alt:   (downloads)
.. |docker_bioconductor-yeast2.db| image:: https://quay.io/repository/biocontainers/bioconductor-yeast2.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-yeast2.db
.. _`bioconductor-yeast2.db/tags`: https://quay.io/repository/biocontainers/bioconductor-yeast2.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-yeast2.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-yeast2.db/README.html