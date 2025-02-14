:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rfarm'
.. highlight: bash

bioconductor-rfarm
==================

.. conda:recipe:: bioconductor-rfarm
   :replaces_section_title:
   :noindex:

   An R interface to the Rfam database

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/rfaRm.html
   :license: GPL-3
   :recipe: /`bioconductor-rfarm <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rfarm>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rfarm/meta.yaml>`_

   rfaRm provides a client interface to the Rfam database of RNA families. Data that can be retrieved include RNA families\, secondary structure images\, covariance models\, sequences within each family\, alignments leading to the identification of a family and secondary structures in the dot\-bracket format.


.. conda:package:: bioconductor-rfarm

   |downloads_bioconductor-rfarm| |docker_bioconductor-rfarm|

   :versions:
      
      

      ``1.2.1-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-httr: 
   :depends r-magick: 
   :depends r-rsvg: 
   :depends r-rvest: 
   :depends r-stringi: 
   :depends r-xml2: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rfarm

   and update with::

      conda update bioconductor-rfarm

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rfarm:<tag>

   (see `bioconductor-rfarm/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rfarm| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rfarm.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rfarm
   :alt:   (downloads)
.. |docker_bioconductor-rfarm| image:: https://quay.io/repository/biocontainers/bioconductor-rfarm/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rfarm
.. _`bioconductor-rfarm/tags`: https://quay.io/repository/biocontainers/bioconductor-rfarm?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rfarm/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rfarm/README.html