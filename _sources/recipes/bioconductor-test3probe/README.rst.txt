:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-test3probe'
.. highlight: bash

bioconductor-test3probe
=======================

.. conda:recipe:: bioconductor-test3probe
   :replaces_section_title:
   :noindex:

   Probe sequence data for microarrays of type test3

   :homepage: https://bioconductor.org/packages/3.12/data/annotation/html/test3probe.html
   :license: LGPL
   :recipe: /`bioconductor-test3probe <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-test3probe>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-test3probe/meta.yaml>`_

   This package was automatically created by package AnnotationForge version 1.11.21. The probe sequence data was obtained from http\:\/\/www.affymetrix.com. The file name was Test3\\\_probe\\\_tab.


.. conda:package:: bioconductor-test3probe

   |downloads_bioconductor-test3probe| |docker_bioconductor-test3probe|

   :versions:
      
      

      ``2.18.0-6``,  ``2.18.0-5``,  ``2.18.0-4``,  ``2.18.0-3``,  ``2.18.0-2``,  ``2.18.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-test3probe

   and update with::

      conda update bioconductor-test3probe

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-test3probe:<tag>

   (see `bioconductor-test3probe/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-test3probe| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-test3probe.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-test3probe
   :alt:   (downloads)
.. |docker_bioconductor-test3probe| image:: https://quay.io/repository/biocontainers/bioconductor-test3probe/status
   :target: https://quay.io/repository/biocontainers/bioconductor-test3probe
.. _`bioconductor-test3probe/tags`: https://quay.io/repository/biocontainers/bioconductor-test3probe?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-test3probe/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-test3probe/README.html