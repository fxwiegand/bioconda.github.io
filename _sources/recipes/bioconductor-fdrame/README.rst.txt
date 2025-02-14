:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fdrame'
.. highlight: bash

bioconductor-fdrame
===================

.. conda:recipe:: bioconductor-fdrame
   :replaces_section_title:
   :noindex:

   FDR adjustments of Microarray Experiments \(FDR\-AME\)

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/fdrame.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-fdrame <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fdrame>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fdrame/meta.yaml>`_

   This package contains two main functions. The first is fdr.ma which takes normalized expression data array\, experimental design and computes adjusted p\-values It returns the fdr adjusted p\-values and plots\, according to the methods described in \(Reiner\, Yekutieli and Benjamini 2002\). The second\, is fdr.gui\(\) which creates a simple graphic user interface to access fdr.ma


.. conda:package:: bioconductor-fdrame

   |downloads_bioconductor-fdrame| |docker_bioconductor-fdrame|

   :versions:
      
      

      ``1.62.0-1``,  ``1.62.0-0``,  ``1.60.0-0``,  ``1.58.0-0``,  ``1.56.0-1``,  ``1.56.0-0``,  ``1.54.0-0``

      

   
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-fdrame

   and update with::

      conda update bioconductor-fdrame

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fdrame:<tag>

   (see `bioconductor-fdrame/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fdrame| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fdrame.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fdrame
   :alt:   (downloads)
.. |docker_bioconductor-fdrame| image:: https://quay.io/repository/biocontainers/bioconductor-fdrame/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fdrame
.. _`bioconductor-fdrame/tags`: https://quay.io/repository/biocontainers/bioconductor-fdrame?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fdrame/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fdrame/README.html