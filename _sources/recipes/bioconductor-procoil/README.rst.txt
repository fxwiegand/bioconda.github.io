:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-procoil'
.. highlight: bash

bioconductor-procoil
====================

.. conda:recipe:: bioconductor-procoil
   :replaces_section_title:
   :noindex:

   Prediction of Oligomerization of Coiled Coil Proteins

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/procoil.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-procoil <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-procoil>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-procoil/meta.yaml>`_
   :links: biotools: :biotools:`procoil`

   The package allows for predicting whether a coiled coil sequence \(amino acid sequence plus heptad register\) is more likely to form a dimer or more likely to form a trimer. Additionally to the prediction itself\, a prediction profile is computed which allows for determining the strengths to which the individual residues are indicative for either class. Prediction profiles can also be visualized as curves or heatmaps.


.. conda:package:: bioconductor-procoil

   |downloads_bioconductor-procoil| |docker_bioconductor-procoil|

   :versions:
      
      

      ``2.18.0-1``,  ``2.18.0-0``,  ``2.16.0-0``,  ``2.14.0-0``,  ``2.12.0-1``,  ``2.10.0-0``,  ``2.8.0-0``,  ``2.6.0-0``

      

   
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-kebabs: ``>=1.24.0,<1.25.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-procoil

   and update with::

      conda update bioconductor-procoil

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-procoil:<tag>

   (see `bioconductor-procoil/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-procoil| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-procoil.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-procoil
   :alt:   (downloads)
.. |docker_bioconductor-procoil| image:: https://quay.io/repository/biocontainers/bioconductor-procoil/status
   :target: https://quay.io/repository/biocontainers/bioconductor-procoil
.. _`bioconductor-procoil/tags`: https://quay.io/repository/biocontainers/bioconductor-procoil?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-procoil/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-procoil/README.html