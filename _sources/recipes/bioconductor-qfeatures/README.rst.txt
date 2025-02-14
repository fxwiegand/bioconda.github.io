:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-qfeatures'
.. highlight: bash

bioconductor-qfeatures
======================

.. conda:recipe:: bioconductor-qfeatures
   :replaces_section_title:
   :noindex:

   Quantitative features for mass spectrometry data

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/QFeatures.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-qfeatures <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qfeatures>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-qfeatures/meta.yaml>`_

   The QFeatures infrastructure enables the management and processing of quantitative features for high\-throughput mass spectrometry assays. It provides a familiar Bioconductor user experience to manages quantitative data across different assay levels \(such as peptide spectrum matches\, peptides and proteins\) in a coherent and tractable format.


.. conda:package:: bioconductor-qfeatures

   |downloads_bioconductor-qfeatures| |docker_bioconductor-qfeatures|

   :versions:
      
      

      ``1.0.0-2``,  ``1.0.0-1``

      

   
   :depends bioconductor-annotationfilter: ``>=1.14.0,<1.15.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-mscoreutils: ``>=1.2.0,<1.3.0``
   :depends bioconductor-multiassayexperiment: ``>=1.16.0,<1.17.0``
   :depends bioconductor-protgenerics: ``>=1.22.0,<1.23.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-lazyeval: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-qfeatures

   and update with::

      conda update bioconductor-qfeatures

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-qfeatures:<tag>

   (see `bioconductor-qfeatures/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-qfeatures| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-qfeatures.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-qfeatures
   :alt:   (downloads)
.. |docker_bioconductor-qfeatures| image:: https://quay.io/repository/biocontainers/bioconductor-qfeatures/status
   :target: https://quay.io/repository/biocontainers/bioconductor-qfeatures
.. _`bioconductor-qfeatures/tags`: https://quay.io/repository/biocontainers/bioconductor-qfeatures?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-qfeatures/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-qfeatures/README.html