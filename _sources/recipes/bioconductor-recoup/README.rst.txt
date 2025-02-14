:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-recoup'
.. highlight: bash

bioconductor-recoup
===================

.. conda:recipe:: bioconductor-recoup
   :replaces_section_title:
   :noindex:

   An R package for the creation of complex genomic profile plots

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/recoup.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-recoup <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-recoup>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-recoup/meta.yaml>`_
   :links: biotools: :biotools:`recoup`, doi: :doi:`10.1038/nmeth.3252`

   recoup calculates and plots signal profiles created from short sequence reads derived from Next Generation Sequencing technologies. The profiles provided are either sumarized curve profiles or heatmap profiles. Currently\, recoup supports genomic profile plots for reads derived from ChIP\-Seq and RNA\-Seq experiments. The package uses ggplot2 and ComplexHeatmap graphics facilities for curve and heatmap coverage profiles respectively.


.. conda:package:: bioconductor-recoup

   |downloads_bioconductor-recoup| |docker_bioconductor-recoup|

   :versions:
      
      

      ``1.18.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-1``,  ``1.10.0-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-biomart: ``>=2.46.0,<2.47.0``
   :depends bioconductor-complexheatmap: ``>=2.6.0,<2.7.0``
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicalignments: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-circlize: 
   :depends r-ggplot2: 
   :depends r-httr: 
   :depends r-rsqlite: 
   :depends r-stringr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-recoup

   and update with::

      conda update bioconductor-recoup

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-recoup:<tag>

   (see `bioconductor-recoup/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-recoup| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-recoup.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-recoup
   :alt:   (downloads)
.. |docker_bioconductor-recoup| image:: https://quay.io/repository/biocontainers/bioconductor-recoup/status
   :target: https://quay.io/repository/biocontainers/bioconductor-recoup
.. _`bioconductor-recoup/tags`: https://quay.io/repository/biocontainers/bioconductor-recoup?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-recoup/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-recoup/README.html