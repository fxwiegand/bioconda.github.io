:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rnaeditr'
.. highlight: bash

bioconductor-rnaeditr
=====================

.. conda:recipe:: bioconductor-rnaeditr
   :replaces_section_title:
   :noindex:

   Statistical analysis of RNA editing sites and hyper\-editing regions

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/rnaEditr.html
   :license: GPL-3
   :recipe: /`bioconductor-rnaeditr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnaeditr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnaeditr/meta.yaml>`_

   RNAeditr analyzes site\-specific RNA editing events\, as well as hyper\-editing regions. The editing frequencies can be tested against binary\, continuous or survival outcomes. Multiple covariate variables as well as interaction effects can also be incorporated in the statistical models.


.. conda:package:: bioconductor-rnaeditr

   |downloads_bioconductor-rnaeditr| |docker_bioconductor-rnaeditr|

   :versions:
      
      

      ``1.0.0-2``,  ``1.0.0-1``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-bumphunter: ``>=1.32.0,<1.33.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-corrplot: 
   :depends r-logistf: 
   :depends r-plyr: 
   :depends r-survival: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rnaeditr

   and update with::

      conda update bioconductor-rnaeditr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rnaeditr:<tag>

   (see `bioconductor-rnaeditr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rnaeditr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rnaeditr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rnaeditr
   :alt:   (downloads)
.. |docker_bioconductor-rnaeditr| image:: https://quay.io/repository/biocontainers/bioconductor-rnaeditr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rnaeditr
.. _`bioconductor-rnaeditr/tags`: https://quay.io/repository/biocontainers/bioconductor-rnaeditr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rnaeditr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rnaeditr/README.html