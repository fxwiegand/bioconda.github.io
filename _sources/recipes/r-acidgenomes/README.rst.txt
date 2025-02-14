:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-acidgenomes'
.. highlight: bash

r-acidgenomes
=============

.. conda:recipe:: r-acidgenomes
   :replaces_section_title:
   :noindex:

   Toolkit for downloading and processing genome annotations.

   :homepage: https://r.acidgenomics.com/packages/acidgenomes/
   :developer docs: https://github.com/acidgenomics/r-acidgenomes
   :license: GPL / AGPL-3.0
   :recipe: /`r-acidgenomes <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-acidgenomes>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-acidgenomes/meta.yaml>`_

   


.. conda:package:: r-acidgenomes

   |downloads_r-acidgenomes| |docker_r-acidgenomes|

   :versions:
      
      

      ``0.2.11-2``,  ``0.2.11-0``,  ``0.1.1-1``,  ``0.1.1-0``

      

   
   :depends bioconductor-annotationdbi: ``>=1.52``
   :depends bioconductor-annotationhub: ``>=2.22``
   :depends bioconductor-biomart: ``>=2.46``
   :depends bioconductor-ensdb.hsapiens.v75: ``>=2.99``
   :depends bioconductor-ensembldb: ``>=2.14``
   :depends bioconductor-genomeinfodb: ``>=1.26``
   :depends bioconductor-genomicfeatures: ``>=1.42``
   :depends r-acidbase: ``>=0.3.13``
   :depends r-acidcli: ``>=0.1.0``
   :depends r-acidgenerics: ``>=0.5.17``
   :depends r-acidplyr: ``>=0.1.17``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-goalie: ``>=0.5.1``
   :depends r-httr: ``>=1.4``
   :depends r-pipette: ``>=0.5.14``
   :depends r-stringr: ``>=1.4``
   :depends r-syntactic: ``>=0.4.4``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-acidgenomes

   and update with::

      conda update r-acidgenomes

   or use the docker container::

      docker pull quay.io/biocontainers/r-acidgenomes:<tag>

   (see `r-acidgenomes/tags`_ for valid values for ``<tag>``)


.. |downloads_r-acidgenomes| image:: https://img.shields.io/conda/dn/bioconda/r-acidgenomes.svg?style=flat
   :target: https://anaconda.org/bioconda/r-acidgenomes
   :alt:   (downloads)
.. |docker_r-acidgenomes| image:: https://quay.io/repository/biocontainers/r-acidgenomes/status
   :target: https://quay.io/repository/biocontainers/r-acidgenomes
.. _`r-acidgenomes/tags`: https://quay.io/repository/biocontainers/r-acidgenomes?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-acidgenomes/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-acidgenomes/README.html