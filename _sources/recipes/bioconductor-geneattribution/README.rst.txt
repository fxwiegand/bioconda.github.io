:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-geneattribution'
.. highlight: bash

bioconductor-geneattribution
============================

.. conda:recipe:: bioconductor-geneattribution
   :replaces_section_title:
   :noindex:

   Identification of candidate genes associated with genetic variation

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/geneAttribution.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-geneattribution <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geneattribution>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-geneattribution/meta.yaml>`_
   :links: biotools: :biotools:`geneattribution`, doi: :doi:`10.1093/bioinformatics/btw698`

   Identification of the most likely gene or genes through which variation at a given genomic locus in the human genome acts. The most basic functionality assumes that the closer gene is to the input locus\, the more likely the gene is to be causative. Additionally\, any empirical data that links genomic regions to genes \(e.g. eQTL or genome conformation data\) can be used if it is supplied in the UCSC .BED file format.


.. conda:package:: bioconductor-geneattribution

   |downloads_bioconductor-geneattribution| |docker_bioconductor-geneattribution|

   :versions:
      
      

      ``1.16.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-geneattribution

   and update with::

      conda update bioconductor-geneattribution

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-geneattribution:<tag>

   (see `bioconductor-geneattribution/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-geneattribution| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-geneattribution.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-geneattribution
   :alt:   (downloads)
.. |docker_bioconductor-geneattribution| image:: https://quay.io/repository/biocontainers/bioconductor-geneattribution/status
   :target: https://quay.io/repository/biocontainers/bioconductor-geneattribution
.. _`bioconductor-geneattribution/tags`: https://quay.io/repository/biocontainers/bioconductor-geneattribution?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-geneattribution/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-geneattribution/README.html