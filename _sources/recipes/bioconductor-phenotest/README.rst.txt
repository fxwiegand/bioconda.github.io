:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-phenotest'
.. highlight: bash

bioconductor-phenotest
======================

.. conda:recipe:: bioconductor-phenotest
   :replaces_section_title:
   :noindex:

   Tools to test association between gene expression and phenotype in a way that is efficient\, structured\, fast and scalable. We also provide tools to do GSEA \(Gene set enrichment analysis\) and copy number variation.

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/phenoTest.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-phenotest <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-phenotest>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-phenotest/meta.yaml>`_

   Tools to test correlation between gene expression and phenotype in a way that is efficient\, structured\, fast and scalable. GSEA is also provided.


.. conda:package:: bioconductor-phenotest

   |downloads_bioconductor-phenotest| |docker_bioconductor-phenotest|

   :versions:
      
      

      ``1.38.0-1``,  ``1.38.0-0``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-1``,  ``1.30.0-0``

      

   
   :depends bioconductor-annotate: ``>=1.68.0,<1.69.0``
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biomart: ``>=2.46.0,<2.47.0``
   :depends bioconductor-category: ``>=2.56.0,<2.57.0``
   :depends bioconductor-genefilter: ``>=1.72.0,<1.73.0``
   :depends bioconductor-gseabase: ``>=1.52.0,<1.53.0``
   :depends bioconductor-heatplus: ``>=2.36.0,<2.37.0``
   :depends bioconductor-hgu133a.db: ``>=3.2.0,<3.3.0``
   :depends bioconductor-hopach: ``>=2.50.0,<2.51.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-bma: 
   :depends r-ellipse: 
   :depends r-ggplot2: 
   :depends r-gplots: 
   :depends r-hmisc: 
   :depends r-mgcv: 
   :depends r-survival: 
   :depends r-xtable: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-phenotest

   and update with::

      conda update bioconductor-phenotest

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-phenotest:<tag>

   (see `bioconductor-phenotest/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-phenotest| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-phenotest.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-phenotest
   :alt:   (downloads)
.. |docker_bioconductor-phenotest| image:: https://quay.io/repository/biocontainers/bioconductor-phenotest/status
   :target: https://quay.io/repository/biocontainers/bioconductor-phenotest
.. _`bioconductor-phenotest/tags`: https://quay.io/repository/biocontainers/bioconductor-phenotest?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-phenotest/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-phenotest/README.html