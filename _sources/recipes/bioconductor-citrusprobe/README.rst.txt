:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-citrusprobe'
.. highlight: bash

bioconductor-citrusprobe
========================

.. conda:recipe:: bioconductor-citrusprobe
   :replaces_section_title:
   :noindex:

   Probe sequence data for microarrays of type citrus

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/citrusprobe.html
   :license: LGPL
   :recipe: /`bioconductor-citrusprobe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-citrusprobe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-citrusprobe/meta.yaml>`_

   This package was automatically created by package AnnotationForge version 1.11.21. The probe sequence data was obtained from http\:\/\/www.affymetrix.com. The file name was Citrus\\\_probe\\\_tab.


.. conda:package:: bioconductor-citrusprobe

   |downloads_bioconductor-citrusprobe| |docker_bioconductor-citrusprobe|

   :versions:
      
      

      ``2.18.0-6``,  ``2.18.0-5``,  ``2.18.0-4``,  ``2.18.0-3``,  ``2.18.0-2``,  ``2.18.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-citrusprobe

   and update with::

      conda update bioconductor-citrusprobe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-citrusprobe:<tag>

   (see `bioconductor-citrusprobe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-citrusprobe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-citrusprobe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-citrusprobe
   :alt:   (downloads)
.. |docker_bioconductor-citrusprobe| image:: https://quay.io/repository/biocontainers/bioconductor-citrusprobe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-citrusprobe
.. _`bioconductor-citrusprobe/tags`: https://quay.io/repository/biocontainers/bioconductor-citrusprobe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-citrusprobe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-citrusprobe/README.html