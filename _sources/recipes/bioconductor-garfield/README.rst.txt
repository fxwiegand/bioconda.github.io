:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-garfield'
.. highlight: bash

bioconductor-garfield
=====================

.. conda:recipe:: bioconductor-garfield
   :replaces_section_title:
   :noindex:

   GWAS Analysis of Regulatory or Functional Information Enrichment with LD correction

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/garfield.html
   :license: GPL-3
   :recipe: /`bioconductor-garfield <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-garfield>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-garfield/meta.yaml>`_

   GARFIELD is a non\-parametric functional enrichment analysis approach described in the paper GARFIELD\: GWAS analysis of regulatory or functional information enrichment with LD correction. Briefly\, it is a method that leverages GWAS findings with regulatory or functional annotations \(primarily from ENCODE and Roadmap epigenomics data\) to find features relevant to a phenotype of interest. It performs greedy pruning of GWAS SNPs \(LD r2 \> 0.1\) and then annotates them based on functional information overlap. Next\, it quantifies Fold Enrichment \(FE\) at various GWAS significance cutoffs and assesses them by permutation testing\, while matching for minor allele frequency\, distance to nearest transcription start site and number of LD proxies \(r2 \> 0.8\).


.. conda:package:: bioconductor-garfield

   |downloads_bioconductor-garfield| |docker_bioconductor-garfield|

   :versions:
      
      

      ``1.18.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.12.0-0``,  ``1.10.0-0``

      

   
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-garfield

   and update with::

      conda update bioconductor-garfield

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-garfield:<tag>

   (see `bioconductor-garfield/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-garfield| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-garfield.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-garfield
   :alt:   (downloads)
.. |docker_bioconductor-garfield| image:: https://quay.io/repository/biocontainers/bioconductor-garfield/status
   :target: https://quay.io/repository/biocontainers/bioconductor-garfield
.. _`bioconductor-garfield/tags`: https://quay.io/repository/biocontainers/bioconductor-garfield?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-garfield/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-garfield/README.html