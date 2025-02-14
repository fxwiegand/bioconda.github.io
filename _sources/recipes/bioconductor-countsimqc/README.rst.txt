:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-countsimqc'
.. highlight: bash

bioconductor-countsimqc
=======================

.. conda:recipe:: bioconductor-countsimqc
   :replaces_section_title:
   :noindex:

   Compare Characteristic Features of Count Data Sets

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/countsimQC.html
   :license: GPL (>=2)
   :recipe: /`bioconductor-countsimqc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-countsimqc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-countsimqc/meta.yaml>`_

   countsimQC provides functionality to create a comprehensive report comparing a broad range of characteristics across a collection of count matrices. One important use case is the comparison of one or more synthetic count matrices to a real count matrix\, possibly the one underlying the simulations. However\, any collection of count matrices can be compared.


.. conda:package:: bioconductor-countsimqc

   |downloads_bioconductor-countsimqc| |docker_bioconductor-countsimqc|

   :versions:
      
      

      ``1.8.1-0``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.0.0-0``

      

   
   :depends bioconductor-deseq2: ``>=1.30.0,<1.31.0``
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-genefilter: ``>=1.72.0,<1.73.0``
   :depends bioconductor-genomeinfodbdata: ``>=1.2.0,<1.3.0``
   :depends bioconductor-summarizedexperiment: ``>=1.20.0,<1.21.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-catools: 
   :depends r-dplyr: 
   :depends r-dt: 
   :depends r-ggplot2: 
   :depends r-randtests: 
   :depends r-rmarkdown: ``>=2.5``
   :depends r-tidyr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-countsimqc

   and update with::

      conda update bioconductor-countsimqc

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-countsimqc:<tag>

   (see `bioconductor-countsimqc/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-countsimqc| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-countsimqc.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-countsimqc
   :alt:   (downloads)
.. |docker_bioconductor-countsimqc| image:: https://quay.io/repository/biocontainers/bioconductor-countsimqc/status
   :target: https://quay.io/repository/biocontainers/bioconductor-countsimqc
.. _`bioconductor-countsimqc/tags`: https://quay.io/repository/biocontainers/bioconductor-countsimqc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-countsimqc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-countsimqc/README.html