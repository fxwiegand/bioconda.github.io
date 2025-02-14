:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-annaffy'
.. highlight: bash

bioconductor-annaffy
====================

.. conda:recipe:: bioconductor-annaffy
   :replaces_section_title:
   :noindex:

   Annotation tools for Affymetrix biological metadata

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/annaffy.html
   :license: LGPL
   :recipe: /`bioconductor-annaffy <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-annaffy>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-annaffy/meta.yaml>`_
   :links: biotools: :biotools:`annaffy`, doi: :doi:`10.1038/nmeth.3252`

   Functions for handling data from Bioconductor Affymetrix annotation data packages. Produces compact HTML and text reports including experimental data and URL links to many online databases. Allows searching biological metadata using various criteria.


.. conda:package:: bioconductor-annaffy

   |downloads_bioconductor-annaffy| |docker_bioconductor-annaffy|

   :versions:
      
      

      ``1.62.0-1``,  ``1.62.0-0``,  ``1.60.0-0``,  ``1.58.0-0``,  ``1.56.0-1``,  ``1.54.0-0``,  ``1.52.0-0``,  ``1.50.0-0``,  ``1.48.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-go.db: ``>=3.12.1,<3.13.0``
   :depends bioconductor-kegg.db: ``>=3.2.0,<3.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dbi: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-annaffy

   and update with::

      conda update bioconductor-annaffy

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-annaffy:<tag>

   (see `bioconductor-annaffy/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-annaffy| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-annaffy.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-annaffy
   :alt:   (downloads)
.. |docker_bioconductor-annaffy| image:: https://quay.io/repository/biocontainers/bioconductor-annaffy/status
   :target: https://quay.io/repository/biocontainers/bioconductor-annaffy
.. _`bioconductor-annaffy/tags`: https://quay.io/repository/biocontainers/bioconductor-annaffy?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-annaffy/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-annaffy/README.html