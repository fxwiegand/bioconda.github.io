:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-chimphumanbraindata'
.. highlight: bash

bioconductor-chimphumanbraindata
================================

.. conda:recipe:: bioconductor-chimphumanbraindata
   :replaces_section_title:
   :noindex:

   Chimp and human brain data package

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/ChimpHumanBrainData.html
   :license: MIT
   :recipe: /`bioconductor-chimphumanbraindata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chimphumanbraindata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-chimphumanbraindata/meta.yaml>`_

   This data package contains chimp and human brain data extracted from the ArrayExpress accession E\-AFMX\-2.  Both human and chimp RNAs were run on human hgu95av2 Affymetrix arrays. It is a useful dataset for tutorials.


.. conda:package:: bioconductor-chimphumanbraindata

   |downloads_bioconductor-chimphumanbraindata| |docker_bioconductor-chimphumanbraindata|

   :versions:
      
      

      ``1.28.0-1``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-1``,  ``1.20.0-0``

      

   
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-qvalue: ``>=2.22.0,<2.23.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-hexbin: 
   :depends r-statmod: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-chimphumanbraindata

   and update with::

      conda update bioconductor-chimphumanbraindata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-chimphumanbraindata:<tag>

   (see `bioconductor-chimphumanbraindata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-chimphumanbraindata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-chimphumanbraindata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-chimphumanbraindata
   :alt:   (downloads)
.. |docker_bioconductor-chimphumanbraindata| image:: https://quay.io/repository/biocontainers/bioconductor-chimphumanbraindata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-chimphumanbraindata
.. _`bioconductor-chimphumanbraindata/tags`: https://quay.io/repository/biocontainers/bioconductor-chimphumanbraindata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-chimphumanbraindata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-chimphumanbraindata/README.html