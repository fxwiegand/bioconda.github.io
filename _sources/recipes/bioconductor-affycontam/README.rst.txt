:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-affycontam'
.. highlight: bash

bioconductor-affycontam
=======================

.. conda:recipe:: bioconductor-affycontam
   :replaces_section_title:
   :noindex:

   structured corruption of affymetrix cel file data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/affyContam.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-affycontam <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affycontam>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affycontam/meta.yaml>`_
   :links: biotools: :biotools:`affycontam`, doi: :doi:`10.1038/nmeth.3252`

   structured corruption of cel file data to demonstrate QA effectiveness


.. conda:package:: bioconductor-affycontam

   |downloads_bioconductor-affycontam| |docker_bioconductor-affycontam|

   :versions:
      
      

      ``1.48.0-1``,  ``1.48.0-0``,  ``1.46.0-0``,  ``1.44.0-1``,  ``1.42.0-1``,  ``1.40.0-0``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``

      

   
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends bioconductor-affydata: ``>=1.38.0,<1.39.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-affycontam

   and update with::

      conda update bioconductor-affycontam

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-affycontam:<tag>

   (see `bioconductor-affycontam/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-affycontam| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-affycontam.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-affycontam
   :alt:   (downloads)
.. |docker_bioconductor-affycontam| image:: https://quay.io/repository/biocontainers/bioconductor-affycontam/status
   :target: https://quay.io/repository/biocontainers/bioconductor-affycontam
.. _`bioconductor-affycontam/tags`: https://quay.io/repository/biocontainers/bioconductor-affycontam?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-affycontam/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-affycontam/README.html