:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-bovineprobe'
.. highlight: bash

bioconductor-bovineprobe
========================

.. conda:recipe:: bioconductor-bovineprobe
   :replaces_section_title:
   :noindex:

   Probe sequence data for microarrays of type bovine

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/bovineprobe.html
   :license: LGPL
   :recipe: /`bioconductor-bovineprobe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bovineprobe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-bovineprobe/meta.yaml>`_

   This package was automatically created by package AnnotationForge version 1.11.21. The probe sequence data was obtained from http\:\/\/www.affymetrix.com. The file name was Bovine\\\_probe\\\_tab.


.. conda:package:: bioconductor-bovineprobe

   |downloads_bioconductor-bovineprobe| |docker_bioconductor-bovineprobe|

   :versions:
      
      

      ``2.18.0-6``,  ``2.18.0-5``,  ``2.18.0-4``,  ``2.18.0-3``,  ``2.18.0-2``,  ``2.18.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-bovineprobe

   and update with::

      conda update bioconductor-bovineprobe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-bovineprobe:<tag>

   (see `bioconductor-bovineprobe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-bovineprobe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-bovineprobe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-bovineprobe
   :alt:   (downloads)
.. |docker_bioconductor-bovineprobe| image:: https://quay.io/repository/biocontainers/bioconductor-bovineprobe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-bovineprobe
.. _`bioconductor-bovineprobe/tags`: https://quay.io/repository/biocontainers/bioconductor-bovineprobe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-bovineprobe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-bovineprobe/README.html