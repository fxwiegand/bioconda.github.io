:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-gofuncr'
.. highlight: bash

bioconductor-gofuncr
====================

.. conda:recipe:: bioconductor-gofuncr
   :replaces_section_title:
   :noindex:

   Gene ontology enrichment using FUNC

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/GOfuncR.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-gofuncr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gofuncr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-gofuncr/meta.yaml>`_

   GOfuncR performs a gene ontology enrichment analysis based on the ontology enrichment software FUNC. GO\-annotations are obtained from OrganismDb or OrgDb packages \(\'Homo.sapiens\' by default\)\; the GO\-graph is included in the package and updated regularly \(23\-Mar\-2020\). GOfuncR provides the standard candidate vs. background enrichment analysis using the hypergeometric test\, as well as three additional tests\: \(i\) the Wilcoxon rank\-sum test that is used when genes are ranked\, \(ii\) a binomial test that is used when genes are associated with two counts and \(iii\) a Chi\-square or Fisher\'s exact test that is used in cases when genes are associated with four counts. To correct for multiple testing and interdependency of the tests\, family\-wise error rates are computed based on random permutations of the gene\-associated variables. GOfuncR also provides tools for exploring the ontology graph and the annotations\, and options to take gene\-length or spatial clustering of genes into account. It is also possible to provide custom gene coordinates\, annotations and ontologies.


.. conda:package:: bioconductor-gofuncr

   |downloads_bioconductor-gofuncr| |docker_bioconductor-gofuncr|

   :versions:
      
      

      ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-1``,  ``1.2.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends libblas: ``>=3.8.0,<4.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends liblapack: ``>=3.8.0,<4.0a0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-gtools: ``>=3.5.0``
   :depends r-mapplots: ``>=1.5``
   :depends r-rcpp: ``>=0.11.5``
   :depends r-vioplot: ``>=0.2``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-gofuncr

   and update with::

      conda update bioconductor-gofuncr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-gofuncr:<tag>

   (see `bioconductor-gofuncr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-gofuncr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-gofuncr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-gofuncr
   :alt:   (downloads)
.. |docker_bioconductor-gofuncr| image:: https://quay.io/repository/biocontainers/bioconductor-gofuncr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-gofuncr
.. _`bioconductor-gofuncr/tags`: https://quay.io/repository/biocontainers/bioconductor-gofuncr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-gofuncr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-gofuncr/README.html