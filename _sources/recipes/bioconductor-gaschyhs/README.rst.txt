:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gaschyhs'
.. highlight: bash

bioconductor-gaschyhs
=====================

.. conda:recipe:: bioconductor-gaschyhs
   :replaces_section_title:
   :noindex:

   ExpressionSet for response of yeast to heat shock and other environmental stresses

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/gaschYHS.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-gaschyhs <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gaschyhs>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gaschyhs/meta.yaml>`_

   Data from PMID 11102521


.. conda:package:: bioconductor-gaschyhs

   |downloads_bioconductor-gaschyhs| |docker_bioconductor-gaschyhs|

   :versions:
      
      

      ``1.28.0-1``,  ``1.28.0-0``,  ``1.27.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.20.0-0``

      

   
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gaschyhs

   and update with::

      conda update bioconductor-gaschyhs

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gaschyhs:<tag>

   (see `bioconductor-gaschyhs/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gaschyhs| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gaschyhs.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gaschyhs
   :alt:   (downloads)
.. |docker_bioconductor-gaschyhs| image:: https://quay.io/repository/biocontainers/bioconductor-gaschyhs/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gaschyhs
.. _`bioconductor-gaschyhs/tags`: https://quay.io/repository/biocontainers/bioconductor-gaschyhs?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gaschyhs/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gaschyhs/README.html