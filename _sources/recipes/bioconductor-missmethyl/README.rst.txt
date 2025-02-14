:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-missmethyl'
.. highlight: bash

bioconductor-missmethyl
=======================

.. conda:recipe:: bioconductor-missmethyl
   :replaces_section_title:
   :noindex:

   Analysing Illumina HumanMethylation BeadChip Data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/missMethyl.html
   :license: GPL-2
   :recipe: /`bioconductor-missmethyl <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-missmethyl>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-missmethyl/meta.yaml>`_
   :links: biotools: :biotools:`missmethyl`

   Normalisation\, testing for differential variability and differential methylation and gene set testing for data from Illumina\'s Infinium HumanMethylation arrays. The normalisation procedure is subset\-quantile within\-array normalisation \(SWAN\)\, which allows Infinium I and II type probes on a single array to be normalised together. The test for differential variability is based on an empirical Bayes version of Levene\'s test. Differential methylation testing is performed using RUV\, which can adjust for systematic errors of unknown origin in high\-dimensional data by using negative control probes. Gene ontology analysis is performed by taking into account the number of probes per gene on the array\, as well as taking into account multi\-gene associated probes.


.. conda:package:: bioconductor-missmethyl

   |downloads_bioconductor-missmethyl| |docker_bioconductor-missmethyl|

   :versions:
      
      

      ``1.24.0-1``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-go.db: ``>=3.12.1,<3.13.0``
   :depends bioconductor-illuminahumanmethylation450kanno.ilmn12.hg19: ``>=0.6.0,<0.7.0``
   :depends bioconductor-illuminahumanmethylation450kmanifest: ``>=0.4.0,<0.5.0``
   :depends bioconductor-illuminahumanmethylationepicanno.ilm10b4.hg19: ``>=0.6.0,<0.7.0``
   :depends bioconductor-illuminahumanmethylationepicmanifest: ``>=0.3.0,<0.4.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-methylumi: ``>=2.36.0,<2.37.0``
   :depends bioconductor-minfi: ``>=1.36.0,<1.37.0``
   :depends bioconductor-org.hs.eg.db: ``>=3.12.0,<3.13.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-biasedurn: 
   :depends r-ruv: 
   :depends r-statmod: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-missmethyl

   and update with::

      conda update bioconductor-missmethyl

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-missmethyl:<tag>

   (see `bioconductor-missmethyl/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-missmethyl| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-missmethyl.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-missmethyl
   :alt:   (downloads)
.. |docker_bioconductor-missmethyl| image:: https://quay.io/repository/biocontainers/bioconductor-missmethyl/status
   :target: https://quay.io/repository/biocontainers/bioconductor-missmethyl
.. _`bioconductor-missmethyl/tags`: https://quay.io/repository/biocontainers/bioconductor-missmethyl?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-missmethyl/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-missmethyl/README.html