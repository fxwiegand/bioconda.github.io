:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-benchmarkfdrdata2019'
.. highlight: bash

bioconductor-benchmarkfdrdata2019
=================================

.. conda:recipe:: bioconductor-benchmarkfdrdata2019
   :replaces_section_title:
   :noindex:

   Data and Benchmarking Results from Korthauer and Kimes et al. \(2019\)

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/benchmarkfdrData2019.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-benchmarkfdrdata2019 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-benchmarkfdrdata2019>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-benchmarkfdrdata2019/meta.yaml>`_

   Benchmarking results for experimental and simulated data sets used in Korthauer and Kimes et al. \(2019\) to compare methods for controlling the false discovery rate.


.. conda:package:: bioconductor-benchmarkfdrdata2019

   |downloads_bioconductor-benchmarkfdrdata2019| |docker_bioconductor-benchmarkfdrdata2019|

   :versions:
      
      

      ``1.4.0-1``,  ``1.4.0-0``,  ``1.2.0-0``,  ``1.0.0-0``

      

   
   :depends bioconductor-experimenthub: ``>=1.16.0,<1.17.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-benchmarkfdrdata2019

   and update with::

      conda update bioconductor-benchmarkfdrdata2019

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-benchmarkfdrdata2019:<tag>

   (see `bioconductor-benchmarkfdrdata2019/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-benchmarkfdrdata2019| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-benchmarkfdrdata2019.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-benchmarkfdrdata2019
   :alt:   (downloads)
.. |docker_bioconductor-benchmarkfdrdata2019| image:: https://quay.io/repository/biocontainers/bioconductor-benchmarkfdrdata2019/status
   :target: https://quay.io/repository/biocontainers/bioconductor-benchmarkfdrdata2019
.. _`bioconductor-benchmarkfdrdata2019/tags`: https://quay.io/repository/biocontainers/bioconductor-benchmarkfdrdata2019?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-benchmarkfdrdata2019/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-benchmarkfdrdata2019/README.html