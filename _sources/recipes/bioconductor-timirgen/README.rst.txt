:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-timirgen'
.. highlight: bash

bioconductor-timirgen
=====================

.. conda:recipe:: bioconductor-timirgen
   :replaces_section_title:
   :noindex:

   Time sensitive microRNA\-mRNA integration\, analysis and network generation tool

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/TimiRGeN.html
   :license: GPL-3
   :recipe: /`bioconductor-timirgen <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-timirgen>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-timirgen/meta.yaml>`_

   TimiRGeN \(Time Incorporated miR\-mRNA Generation of Networks\) is a novel R package which functionally analyses and integrates time course miRNA\-mRNA differential expression data. This tool can generate small networks within R or export results into cytoscape or pathvisio for more detailed network construction and hypothesis generation. This tool is created for researchers that wish to dive deep into time series multi\-omic datasets. TimiRGeN goes further than many other tools in terms of data reduction. Here\, potentially hundreds of thousands of potential miRNA\-mRNA interactions can be whittled down into a handful of high confidence miRNA\-mRNA interactions effecting a signalling pathway\, across a time course.


.. conda:package:: bioconductor-timirgen

   |downloads_bioconductor-timirgen| |docker_bioconductor-timirgen|

   :versions:
      
      

      ``1.0.3-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-biomart: ``>=2.46.0,<2.47.0``
   :depends bioconductor-clusterprofiler: ``>=3.18.0,<3.19.0``
   :depends bioconductor-mfuzz: ``>=2.50.0,<2.51.0``
   :depends bioconductor-multiassayexperiment: ``>=1.16.0,<1.17.0``
   :depends bioconductor-rcy3: ``>=2.10.0,<2.11.0``
   :depends bioconductor-rwikipathways: ``>=1.10.0,<1.11.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-dplyr: ``>=0.8.4``
   :depends r-ggplot2: 
   :depends r-gtools: ``>=3.8.1``
   :depends r-igraph: ``>=1.2.4.2``
   :depends r-readxl: 
   :depends r-stringr: ``>=1.4.0``
   :depends r-tidyr: ``>=1.0.2``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-timirgen

   and update with::

      conda update bioconductor-timirgen

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-timirgen:<tag>

   (see `bioconductor-timirgen/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-timirgen| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-timirgen.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-timirgen
   :alt:   (downloads)
.. |docker_bioconductor-timirgen| image:: https://quay.io/repository/biocontainers/bioconductor-timirgen/status
   :target: https://quay.io/repository/biocontainers/bioconductor-timirgen
.. _`bioconductor-timirgen/tags`: https://quay.io/repository/biocontainers/bioconductor-timirgen?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-timirgen/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-timirgen/README.html