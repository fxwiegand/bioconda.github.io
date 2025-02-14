:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-dmrscan'
.. highlight: bash

bioconductor-dmrscan
====================

.. conda:recipe:: bioconductor-dmrscan
   :replaces_section_title:
   :noindex:

   Detection of Differentially Methylated Regions

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/DMRScan.html
   :license: GPL-3
   :recipe: /`bioconductor-dmrscan <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrscan>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrscan/meta.yaml>`_

   This package detects significant differentially methylated regions \(for both qualitative and quantitative traits\)\, using a scan statistic with underlying Poisson heuristics. The scan statistic will depend on a sequence of window sizes \(\# of CpGs within each window\) and on a threshold for each window size. This threshold can be calculated by three different means\: i\) analytically using Siegmund et.al \(2012\) solution \(preferred\)\, ii\) an important sampling as suggested by Zhang \(2008\)\, and a iii\) full MCMC modeling of the data\, choosing between a number of different options for modeling the dependency between each CpG.


.. conda:package:: bioconductor-dmrscan

   |downloads_bioconductor-dmrscan| |docker_bioconductor-dmrscan|

   :versions:
      
      

      ``1.12.0-1``,  ``1.12.0-0``,  ``1.11.0-0``,  ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``

      

   
   :depends bioconductor-genomeinfodb: ``>=1.26.0,<1.27.0``
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-mass: 
   :depends r-matrix: 
   :depends r-mvtnorm: 
   :depends r-rcpproll: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-dmrscan

   and update with::

      conda update bioconductor-dmrscan

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-dmrscan:<tag>

   (see `bioconductor-dmrscan/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-dmrscan| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-dmrscan.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-dmrscan
   :alt:   (downloads)
.. |docker_bioconductor-dmrscan| image:: https://quay.io/repository/biocontainers/bioconductor-dmrscan/status
   :target: https://quay.io/repository/biocontainers/bioconductor-dmrscan
.. _`bioconductor-dmrscan/tags`: https://quay.io/repository/biocontainers/bioconductor-dmrscan?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-dmrscan/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-dmrscan/README.html