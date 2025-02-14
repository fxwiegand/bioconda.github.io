:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-spidermir'
.. highlight: bash

bioconductor-spidermir
======================

.. conda:recipe:: bioconductor-spidermir
   :replaces_section_title:
   :noindex:

   SpidermiR\: An R\/Bioconductor package for integrative network analysis with miRNA data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/SpidermiR.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-spidermir <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spidermir>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-spidermir/meta.yaml>`_
   :links: biotools: :biotools:`spidermir`, doi: :doi:`10.3390/ijms18020274`

   The aims of SpidermiR are \: i\) facilitate the network open\-access data retrieval from GeneMania data\, ii\) prepare the data using the appropriate gene nomenclature\, iii\) integration of miRNA data in a specific network\, iv\) provide different standard analyses and v\) allow the user to visualize the results. In more detail\, the package provides multiple methods for query\, prepare and download network data \(GeneMania\)\, and the integration with validated and predicted miRNA data \(mirWalk\, miRTarBase\, miRandola\, Miranda\, PicTar and TargetScan\). Furthermore\, we also present a statistical test to identify pharmaco\-mir relationships using the gene\-drug interactions derived by DGIdb and MATADOR database.


.. conda:package:: bioconductor-spidermir

   |downloads_bioconductor-spidermir| |docker_bioconductor-spidermir|

   :versions:
      
      

      ``1.20.0-1``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-1``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.2-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-mageckflute: ``>=1.10.0,<1.11.0``
   :depends bioconductor-mirnatap: ``>=1.23.0,<1.24.0``
   :depends bioconductor-mirnatap.db: ``>=0.99.0,<0.100.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends bioconductor-tcgabiolinks: ``>=2.18.0,<2.19.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-gdata: 
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-gridextra: 
   :depends r-httr: 
   :depends r-igraph: 
   :depends r-lattice: 
   :depends r-latticeextra: 
   :depends r-networkd3: 
   :depends r-visnetwork: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-spidermir

   and update with::

      conda update bioconductor-spidermir

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-spidermir:<tag>

   (see `bioconductor-spidermir/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-spidermir| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-spidermir.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-spidermir
   :alt:   (downloads)
.. |docker_bioconductor-spidermir| image:: https://quay.io/repository/biocontainers/bioconductor-spidermir/status
   :target: https://quay.io/repository/biocontainers/bioconductor-spidermir
.. _`bioconductor-spidermir/tags`: https://quay.io/repository/biocontainers/bioconductor-spidermir?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-spidermir/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-spidermir/README.html