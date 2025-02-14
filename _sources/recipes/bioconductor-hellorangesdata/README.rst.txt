:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-hellorangesdata'
.. highlight: bash

bioconductor-hellorangesdata
============================

.. conda:recipe:: bioconductor-hellorangesdata
   :replaces_section_title:
   :noindex:

   Data for the HelloRanges tutorial vignette

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/HelloRangesData.html
   :license: GPL (>= 2)
   :recipe: /`bioconductor-hellorangesdata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hellorangesdata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-hellorangesdata/meta.yaml>`_

   Provides the data that were used in the bedtools tutorial by Aaron Quinlan \(http\:\/\/quinlanlab.org\/tutorials\/bedtools\/bedtools.html\). Includes a subset of the DnaseI hypersensitivity data from \"Maurano et al. Systematic Localization of Common Disease\-Associated Variation in Regulatory DNA. Science. 2012. Vol. 337 no. 6099 pp. 1190\-1195.\" The rest of the tracks were originally downloaded from the UCSC table browser. See the HelloRanges vignette for a port of the bedtools tutorial to R.


.. conda:package:: bioconductor-hellorangesdata

   |downloads_bioconductor-hellorangesdata| |docker_bioconductor-hellorangesdata|

   :versions:
      
      

      ``1.16.0-1``,  ``1.16.0-0``,  ``1.15.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-1``,  ``1.10.0-0``,  ``1.8.0-0``

      

   
   :depends curl: ``>=7.75.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-hellorangesdata

   and update with::

      conda update bioconductor-hellorangesdata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-hellorangesdata:<tag>

   (see `bioconductor-hellorangesdata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-hellorangesdata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-hellorangesdata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-hellorangesdata
   :alt:   (downloads)
.. |docker_bioconductor-hellorangesdata| image:: https://quay.io/repository/biocontainers/bioconductor-hellorangesdata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-hellorangesdata
.. _`bioconductor-hellorangesdata/tags`: https://quay.io/repository/biocontainers/bioconductor-hellorangesdata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-hellorangesdata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-hellorangesdata/README.html