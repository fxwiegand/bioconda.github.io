:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-omicsprint'
.. highlight: bash

bioconductor-omicsprint
=======================

.. conda:recipe:: bioconductor-omicsprint
   :replaces_section_title:
   :noindex:

   Cross omic genetic fingerprinting

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/omicsPrint.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-omicsprint <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-omicsprint>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-omicsprint/meta.yaml>`_

   omicsPrint provides functionality for cross omic genetic fingerprinting\, for example\, to verify sample relationships between multiple omics data types\, i.e. genomic\, transcriptomic and epigenetic \(DNA methylation\).


.. conda:package:: bioconductor-omicsprint

   |downloads_bioconductor-omicsprint| |docker_bioconductor-omicsprint|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.2.1-0``,  ``1.2.0-0``

      

   
   :depends bioconductor-multiassayexperiment: ``>=1.16.0,<1.17.0``
   :depends bioconductor-raggedexperiment: ``>=1.14.0,<1.15.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-mass: 
   :depends r-matrixstats: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-omicsprint

   and update with::

      conda update bioconductor-omicsprint

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-omicsprint:<tag>

   (see `bioconductor-omicsprint/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-omicsprint| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-omicsprint.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-omicsprint
   :alt:   (downloads)
.. |docker_bioconductor-omicsprint| image:: https://quay.io/repository/biocontainers/bioconductor-omicsprint/status
   :target: https://quay.io/repository/biocontainers/bioconductor-omicsprint
.. _`bioconductor-omicsprint/tags`: https://quay.io/repository/biocontainers/bioconductor-omicsprint?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-omicsprint/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-omicsprint/README.html