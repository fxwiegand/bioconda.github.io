:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mosaicsexample'
.. highlight: bash

bioconductor-mosaicsexample
===========================

.. conda:recipe:: bioconductor-mosaicsexample
   :replaces_section_title:
   :noindex:

   Example data for the mosaics package\, which implements MOSAiCS and MOSAiCS\-HMM\, a statistical framework to analyze one\-sample or two\-sample ChIP\-seq data for transcription factor binding and histone modification

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/mosaicsExample.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-mosaicsexample <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mosaicsexample>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mosaicsexample/meta.yaml>`_

   Data for the mosaics package\, consisting of \(1\) chromosome 22 ChIP and control sample data from a ChIP\-seq experiment of STAT1 binding and H3K4me3 modification in MCF7 cell line from ENCODE database \(HG19\) and \(2\) chromosome 21 ChIP and control sample data from a ChIP\-seq experiment of STAT1 binding\, with mappability\, GC content\, and sequence ambiguity scores of human genome HG18.


.. conda:package:: bioconductor-mosaicsexample

   |downloads_bioconductor-mosaicsexample| |docker_bioconductor-mosaicsexample|

   :versions:
      
      

      ``1.28.0-1``,  ``1.28.0-0``,  ``1.27.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.22.0-0``,  ``1.20.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mosaicsexample

   and update with::

      conda update bioconductor-mosaicsexample

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mosaicsexample:<tag>

   (see `bioconductor-mosaicsexample/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mosaicsexample| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mosaicsexample.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mosaicsexample
   :alt:   (downloads)
.. |docker_bioconductor-mosaicsexample| image:: https://quay.io/repository/biocontainers/bioconductor-mosaicsexample/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mosaicsexample
.. _`bioconductor-mosaicsexample/tags`: https://quay.io/repository/biocontainers/bioconductor-mosaicsexample?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mosaicsexample/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mosaicsexample/README.html