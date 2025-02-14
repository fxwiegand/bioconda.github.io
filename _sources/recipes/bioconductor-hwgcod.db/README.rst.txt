:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hwgcod.db'
.. highlight: bash

bioconductor-hwgcod.db
======================

.. conda:recipe:: bioconductor-hwgcod.db
   :replaces_section_title:
   :noindex:

   Codelink Human Whole Genome Bioarray \(\~55 000 human genes\) annotation data \(chip hwgcod\)

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/hwgcod.db.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-hwgcod.db <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hwgcod.db>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hwgcod.db/meta.yaml>`_

   Codelink Human Whole Genome Bioarray \(\~55 000 human genes\) annotation data \(chip hwgcod\) assembled using data from public repositories


.. conda:package:: bioconductor-hwgcod.db

   |downloads_bioconductor-hwgcod.db| |docker_bioconductor-hwgcod.db|

   :versions:
      
      

      ``3.4.0-6``,  ``3.4.0-5``,  ``3.4.0-4``,  ``3.4.0-3``,  ``3.4.0-2``,  ``3.4.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends curl: ``>=7.76.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hwgcod.db

   and update with::

      conda update bioconductor-hwgcod.db

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hwgcod.db:<tag>

   (see `bioconductor-hwgcod.db/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hwgcod.db| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hwgcod.db.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hwgcod.db
   :alt:   (downloads)
.. |docker_bioconductor-hwgcod.db| image:: https://quay.io/repository/biocontainers/bioconductor-hwgcod.db/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hwgcod.db
.. _`bioconductor-hwgcod.db/tags`: https://quay.io/repository/biocontainers/bioconductor-hwgcod.db?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hwgcod.db/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hwgcod.db/README.html