:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-celegansprobe'
.. highlight: bash

bioconductor-celegansprobe
==========================

.. conda:recipe:: bioconductor-celegansprobe
   :replaces_section_title:
   :noindex:

   Probe sequence data for microarrays of type celegans

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/celegansprobe.html
   :license: LGPL
   :recipe: /`bioconductor-celegansprobe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-celegansprobe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-celegansprobe/meta.yaml>`_

   This package was automatically created by package AnnotationForge version 1.11.21. The probe sequence data was obtained from http\:\/\/www.affymetrix.com. The file name was C\\\_elegans\\\_probe\\\_tab.


.. conda:package:: bioconductor-celegansprobe

   |downloads_bioconductor-celegansprobe| |docker_bioconductor-celegansprobe|

   :versions:
      
      

      ``2.18.0-6``,  ``2.18.0-5``,  ``2.18.0-4``,  ``2.18.0-3``,  ``2.18.0-2``,  ``2.18.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-celegansprobe

   and update with::

      conda update bioconductor-celegansprobe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-celegansprobe:<tag>

   (see `bioconductor-celegansprobe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-celegansprobe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-celegansprobe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-celegansprobe
   :alt:   (downloads)
.. |docker_bioconductor-celegansprobe| image:: https://quay.io/repository/biocontainers/bioconductor-celegansprobe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-celegansprobe
.. _`bioconductor-celegansprobe/tags`: https://quay.io/repository/biocontainers/bioconductor-celegansprobe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-celegansprobe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-celegansprobe/README.html