:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bufferedmatrix'
.. highlight: bash

bioconductor-bufferedmatrix
===========================

.. conda:recipe:: bioconductor-bufferedmatrix
   :replaces_section_title:
   :noindex:

   A matrix data storage object held in temporary files

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/BufferedMatrix.html
   :license: LGPL (>= 2)
   :recipe: /`bioconductor-bufferedmatrix <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bufferedmatrix>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bufferedmatrix/meta.yaml>`_
   :links: biotools: :biotools:`bufferedmatrix`, doi: :doi:`10.1038/nmeth.3252`

   A tabular style data object where most data is stored outside main memory. A buffer is used to speed up access to data.


.. conda:package:: bioconductor-bufferedmatrix

   |downloads_bioconductor-bufferedmatrix| |docker_bioconductor-bufferedmatrix|

   :versions:
      
      

      ``1.54.0-1``,  ``1.54.0-0``,  ``1.52.0-0``,  ``1.50.0-0``,  ``1.48.0-1``,  ``1.48.0-0``,  ``1.46.0-0``,  ``1.44.0-0``,  ``1.42.0-0``

      

   
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bufferedmatrix

   and update with::

      conda update bioconductor-bufferedmatrix

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bufferedmatrix:<tag>

   (see `bioconductor-bufferedmatrix/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bufferedmatrix| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bufferedmatrix.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bufferedmatrix
   :alt:   (downloads)
.. |docker_bioconductor-bufferedmatrix| image:: https://quay.io/repository/biocontainers/bioconductor-bufferedmatrix/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bufferedmatrix
.. _`bioconductor-bufferedmatrix/tags`: https://quay.io/repository/biocontainers/bioconductor-bufferedmatrix?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bufferedmatrix/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bufferedmatrix/README.html