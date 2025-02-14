:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gatefinder'
.. highlight: bash

bioconductor-gatefinder
=======================

.. conda:recipe:: bioconductor-gatefinder
   :replaces_section_title:
   :noindex:

   Projection\-based Gating Strategy Optimization for Flow and Mass Cytometry

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/GateFinder.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-gatefinder <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gatefinder>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gatefinder/meta.yaml>`_

   Given a vector of cluster memberships for a cell population\, identifies a sequence of gates \(polygon filters on 2D scatter plots\) for isolation of that cell type.


.. conda:package:: bioconductor-gatefinder

   |downloads_bioconductor-gatefinder| |docker_bioconductor-gatefinder|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.2.0-0``

      

   
   :depends bioconductor-flowcore: ``>=2.2.0,<2.3.0``
   :depends bioconductor-flowfp: ``>=1.48.0,<1.49.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-diptest: 
   :depends r-mvoutlier: 
   :depends r-splancs: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gatefinder

   and update with::

      conda update bioconductor-gatefinder

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gatefinder:<tag>

   (see `bioconductor-gatefinder/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gatefinder| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gatefinder.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gatefinder
   :alt:   (downloads)
.. |docker_bioconductor-gatefinder| image:: https://quay.io/repository/biocontainers/bioconductor-gatefinder/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gatefinder
.. _`bioconductor-gatefinder/tags`: https://quay.io/repository/biocontainers/bioconductor-gatefinder?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gatefinder/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gatefinder/README.html