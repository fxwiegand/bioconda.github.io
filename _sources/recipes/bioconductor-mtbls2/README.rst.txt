:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-mtbls2'
.. highlight: bash

bioconductor-mtbls2
===================

.. conda:recipe:: bioconductor-mtbls2
   :replaces_section_title:
   :noindex:

   MetaboLights MTBLS2\: Comparative LC\/MS\-based profiling of silver nitrate\-treated Arabidopsis thaliana leaves of wild\-type and cyp79B2 cyp79B3 double knockout plants. Böttcher et al. \(2004\)

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/mtbls2.html
   :license: CC0
   :recipe: /`bioconductor-mtbls2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mtbls2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-mtbls2/meta.yaml>`_

   Indole\-3\-acetaldoxime \(IAOx\) represents an early intermediate of the biosynthesis of a variety of indolic secondary metabolites including the phytoanticipin indol\-3\-ylmethyl glucosinolate and the phytoalexin camalexin \(3\-thiazol\-2\'\-yl\-indole\). Arabidopsis thaliana cyp79B2 cyp79B3 double knockout plants are completely impaired in the conversion of tryptophan to indole\-3\-acetaldoxime and do not accumulate IAOx\-derived metabolites any longer. Consequently\, comparative analysis of wild\-type and cyp79B2 cyp79B3 plant lines has the potential to explore the complete range of IAOx\-derived indolic secondary metabolites.


.. conda:package:: bioconductor-mtbls2

   |downloads_bioconductor-mtbls2| |docker_bioconductor-mtbls2|

   :versions:
      
      

      ``1.20.1-0``,  ``1.19.0-0``,  ``1.17.0-0``,  ``1.16.0-0``,  ``1.14.0-1``,  ``1.14.0-0``,  ``1.12.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-mtbls2

   and update with::

      conda update bioconductor-mtbls2

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-mtbls2:<tag>

   (see `bioconductor-mtbls2/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-mtbls2| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-mtbls2.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-mtbls2
   :alt:   (downloads)
.. |docker_bioconductor-mtbls2| image:: https://quay.io/repository/biocontainers/bioconductor-mtbls2/status
   :target: https://quay.io/repository/biocontainers/bioconductor-mtbls2
.. _`bioconductor-mtbls2/tags`: https://quay.io/repository/biocontainers/bioconductor-mtbls2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-mtbls2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-mtbls2/README.html