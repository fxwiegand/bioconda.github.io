:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rnamodr.ml'
.. highlight: bash

bioconductor-rnamodr.ml
=======================

.. conda:recipe:: bioconductor-rnamodr.ml
   :replaces_section_title:
   :noindex:

   Detecting patterns of post\-transcriptional modifications using machine learning

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/RNAmodR.ML.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-rnamodr.ml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnamodr.ml>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rnamodr.ml/meta.yaml>`_

   RNAmodR.ML extend the functionality of the RNAmodR package and classical detection strategies towards detection through machine learning models. RNAmodR.ML provides classes\, functions and an example workflow to establish a detection stratedy\, which can be packaged.


.. conda:package:: bioconductor-rnamodr.ml

   |downloads_bioconductor-rnamodr.ml| |docker_bioconductor-rnamodr.ml|

   :versions:
      
      

      ``1.4.0-1``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rnamodr: ``>=1.4.0,<1.5.0``
   :depends bioconductor-s4vectors: ``>=0.28.0,<0.29.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ranger: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rnamodr.ml

   and update with::

      conda update bioconductor-rnamodr.ml

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rnamodr.ml:<tag>

   (see `bioconductor-rnamodr.ml/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rnamodr.ml| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rnamodr.ml.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rnamodr.ml
   :alt:   (downloads)
.. |docker_bioconductor-rnamodr.ml| image:: https://quay.io/repository/biocontainers/bioconductor-rnamodr.ml/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rnamodr.ml
.. _`bioconductor-rnamodr.ml/tags`: https://quay.io/repository/biocontainers/bioconductor-rnamodr.ml?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rnamodr.ml/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rnamodr.ml/README.html