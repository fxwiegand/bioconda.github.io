:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-igvr'
.. highlight: bash

bioconductor-igvr
=================

.. conda:recipe:: bioconductor-igvr
   :replaces_section_title:
   :noindex:

   igvR\: integrative genomics viewer

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/igvR.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-igvr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-igvr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-igvr/meta.yaml>`_

   Access to igv.js\, the Integrative Genomics Viewer running in a web browser.


.. conda:package:: bioconductor-igvr

   |downloads_bioconductor-igvr| |docker_bioconductor-igvr|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.7.8-0``,  ``1.6.1-0``,  ``1.4.0-1``,  ``1.2.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-browserviz: ``>=2.12.0,<2.13.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-motifdb: ``>=1.32.0,<1.33.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-seqlogo: ``>=1.56.0,<1.57.0``
   :depends bioconductor-variantannotation: ``>=1.36.0,<1.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-httpuv: 
   :depends r-rcolorbrewer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-igvr

   and update with::

      conda update bioconductor-igvr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-igvr:<tag>

   (see `bioconductor-igvr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-igvr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-igvr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-igvr
   :alt:   (downloads)
.. |docker_bioconductor-igvr| image:: https://quay.io/repository/biocontainers/bioconductor-igvr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-igvr
.. _`bioconductor-igvr/tags`: https://quay.io/repository/biocontainers/bioconductor-igvr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-igvr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-igvr/README.html