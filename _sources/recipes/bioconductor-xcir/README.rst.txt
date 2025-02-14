:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-xcir'
.. highlight: bash

bioconductor-xcir
=================

.. conda:recipe:: bioconductor-xcir
   :replaces_section_title:
   :noindex:

   XCI\-inference

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/XCIR.html
   :license: GPL-2
   :recipe: /`bioconductor-xcir <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xcir>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-xcir/meta.yaml>`_

   Models and tools for subject level analysis of X chromosome inactivation \(XCI\) and XCI\-escape inference.


.. conda:package:: bioconductor-xcir

   |downloads_bioconductor-xcir| |docker_bioconductor-xcir|

   :versions:
      
      

      ``1.4.0-1``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-biomart: ``>=2.46.0,<2.47.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-variantannotation: ``>=1.36.0,<1.37.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-ggplot2: 
   :depends r-readxl: 
   :depends r-seqminer: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-xcir

   and update with::

      conda update bioconductor-xcir

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-xcir:<tag>

   (see `bioconductor-xcir/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-xcir| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-xcir.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-xcir
   :alt:   (downloads)
.. |docker_bioconductor-xcir| image:: https://quay.io/repository/biocontainers/bioconductor-xcir/status
   :target: https://quay.io/repository/biocontainers/bioconductor-xcir
.. _`bioconductor-xcir/tags`: https://quay.io/repository/biocontainers/bioconductor-xcir?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-xcir/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-xcir/README.html