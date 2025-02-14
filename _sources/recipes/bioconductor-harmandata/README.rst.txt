:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-harmandata'
.. highlight: bash

bioconductor-harmandata
=======================

.. conda:recipe:: bioconductor-harmandata
   :replaces_section_title:
   :noindex:

   Data for the Harman package

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/HarmanData.html
   :license: GPL-3
   :recipe: /`bioconductor-harmandata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-harmandata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-harmandata/meta.yaml>`_

   Datasets of accompany Harman\, a PCA and constrained optimisation based technique. Contains three datasets\: IMR90\, Human lung fibroblast cells exposed to nitric oxide\; NPM\, an experiment to test skin penetration of metal oxide nanoparticles following topical application of sunscreens in non\-pregnant mice\; OLF\; an experiment to gauge the response of human olfactory neurosphere\-derived \(hONS\) cells to ZnO nanoparticles.


.. conda:package:: bioconductor-harmandata

   |downloads_bioconductor-harmandata| |docker_bioconductor-harmandata|

   :versions:
      
      

      ``1.18.0-1``,  ``1.18.0-0``,  ``1.17.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.12.0-0``,  ``1.10.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-harmandata

   and update with::

      conda update bioconductor-harmandata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-harmandata:<tag>

   (see `bioconductor-harmandata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-harmandata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-harmandata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-harmandata
   :alt:   (downloads)
.. |docker_bioconductor-harmandata| image:: https://quay.io/repository/biocontainers/bioconductor-harmandata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-harmandata
.. _`bioconductor-harmandata/tags`: https://quay.io/repository/biocontainers/bioconductor-harmandata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-harmandata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-harmandata/README.html