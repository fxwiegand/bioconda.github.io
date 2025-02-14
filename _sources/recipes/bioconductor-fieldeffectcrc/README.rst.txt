:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-fieldeffectcrc'
.. highlight: bash

bioconductor-fieldeffectcrc
===========================

.. conda:recipe:: bioconductor-fieldeffectcrc
   :replaces_section_title:
   :noindex:

   Tumor\, tumor\-adjacent normal\, and healthy colorectal transcriptomes as SummarizedExperiment objects

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/FieldEffectCrc.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-fieldeffectcrc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fieldeffectcrc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-fieldeffectcrc/meta.yaml>`_

   Processed RNA\-seq data for 1\,139 human primary colorectal tissue samples across three phenotypes\, including tumor\, normal adjacent\-to\-tumor\, and healthy\, available as Synapse ID syn22237139 on synapse.org. Data have been parsed into SummarizedExperiment objects available via ExperimentHub to facilitate reproducibility and extension of results from Dampier et al. \(PMCID\: PMC7386360\, PMID\: 32764205\).


.. conda:package:: bioconductor-fieldeffectcrc

   |downloads_bioconductor-fieldeffectcrc| |docker_bioconductor-fieldeffectcrc|

   :versions:
      
      

      ``1.0.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-annotationhub: ``>=2.22.0,<2.23.0``
   :depends bioconductor-biocstyle: ``>=2.18.0,<2.19.0``
   :depends bioconductor-deseq2: ``>=1.30.0,<1.31.0``
   :depends bioconductor-experimenthub: ``>=1.16.0,<1.17.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends curl: ``>=7.76.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-runit: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-fieldeffectcrc

   and update with::

      conda update bioconductor-fieldeffectcrc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-fieldeffectcrc:<tag>

   (see `bioconductor-fieldeffectcrc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-fieldeffectcrc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-fieldeffectcrc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-fieldeffectcrc
   :alt:   (downloads)
.. |docker_bioconductor-fieldeffectcrc| image:: https://quay.io/repository/biocontainers/bioconductor-fieldeffectcrc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-fieldeffectcrc
.. _`bioconductor-fieldeffectcrc/tags`: https://quay.io/repository/biocontainers/bioconductor-fieldeffectcrc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-fieldeffectcrc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-fieldeffectcrc/README.html