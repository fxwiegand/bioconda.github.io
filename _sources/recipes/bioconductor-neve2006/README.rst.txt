:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-neve2006'
.. highlight: bash

bioconductor-neve2006
=====================

.. conda:recipe:: bioconductor-neve2006
   :replaces_section_title:
   :noindex:

   expression and CGH data on breast cancer cell lines

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/Neve2006.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-neve2006 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-neve2006>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-neve2006/meta.yaml>`_

   Experimental organization of combined expression and CGH data


.. conda:package:: bioconductor-neve2006

   |downloads_bioconductor-neve2006| |docker_bioconductor-neve2006|

   :versions:
      
      

      ``0.28.0-1``,  ``0.28.0-0``,  ``0.26.0-0``,  ``0.24.0-0``,  ``0.22.0-1``,  ``0.20.0-0``

      

   
   :depends bioconductor-annotate: ``>=1.68.0,<1.69.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-hgu133a.db: ``>=3.2.0,<3.3.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-neve2006

   and update with::

      conda update bioconductor-neve2006

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-neve2006:<tag>

   (see `bioconductor-neve2006/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-neve2006| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-neve2006.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-neve2006
   :alt:   (downloads)
.. |docker_bioconductor-neve2006| image:: https://quay.io/repository/biocontainers/bioconductor-neve2006/status
   :target: https://quay.io/repository/biocontainers/bioconductor-neve2006
.. _`bioconductor-neve2006/tags`: https://quay.io/repository/biocontainers/bioconductor-neve2006?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-neve2006/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-neve2006/README.html