:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-altcdfenvs'
.. highlight: bash

bioconductor-altcdfenvs
=======================

.. conda:recipe:: bioconductor-altcdfenvs
   :replaces_section_title:
   :noindex:

   alternative CDF environments \(aka probeset mappings\)

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/altcdfenvs.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-altcdfenvs <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-altcdfenvs>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-altcdfenvs/meta.yaml>`_
   :links: biotools: :biotools:`altcdfenvs`

   Convenience data structures and functions to handle cdfenvs


.. conda:package:: bioconductor-altcdfenvs

   |downloads_bioconductor-altcdfenvs| |docker_bioconductor-altcdfenvs|

   :versions:
      
      

      ``2.52.0-1``,  ``2.52.0-0``,  ``2.50.0-0``,  ``2.48.0-0``,  ``2.46.0-1``,  ``2.44.0-0``,  ``2.42.0-0``,  ``2.40.0-0``

      

   
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biostrings: ``>=2.58.0,<2.59.0``
   :depends bioconductor-hypergraph: ``>=1.62.0,<1.63.0``
   :depends bioconductor-makecdfenv: ``>=1.66.0,<1.67.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-altcdfenvs

   and update with::

      conda update bioconductor-altcdfenvs

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-altcdfenvs:<tag>

   (see `bioconductor-altcdfenvs/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-altcdfenvs| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-altcdfenvs.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-altcdfenvs
   :alt:   (downloads)
.. |docker_bioconductor-altcdfenvs| image:: https://quay.io/repository/biocontainers/bioconductor-altcdfenvs/status
   :target: https://quay.io/repository/biocontainers/bioconductor-altcdfenvs
.. _`bioconductor-altcdfenvs/tags`: https://quay.io/repository/biocontainers/bioconductor-altcdfenvs?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-altcdfenvs/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-altcdfenvs/README.html