:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-dmrcatedata'
.. highlight: bash

bioconductor-dmrcatedata
========================

.. conda:recipe:: bioconductor-dmrcatedata
   :replaces_section_title:
   :noindex:

   Data Package for DMRcate

   :homepage: https://bioconductor.org/packages/3.12/data/experiment/html/DMRcatedata.html
   :license: GPL-3
   :recipe: /`bioconductor-dmrcatedata <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrcatedata>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-dmrcatedata/meta.yaml>`_

   This package contains 9 data objects supporting functionality and examples of the Bioconductor package DMRcate.


.. conda:package:: bioconductor-dmrcatedata

   |downloads_bioconductor-dmrcatedata| |docker_bioconductor-dmrcatedata|

   :versions:
      
      

      ``2.8.2-0``,  ``2.8.0-0``,  ``2.6.0-0``,  ``2.2.0-0``,  ``1.20.0-1``,  ``1.18.0-0``,  ``1.16.0-0``,  ``1.14.0-0``

      

   
   :depends bioconductor-experimenthub: ``>=1.16.0,<1.17.0``
   :depends bioconductor-genomicfeatures: ``>=1.42.0,<1.43.0``
   :depends bioconductor-gviz: ``>=1.34.0,<1.35.0``
   :depends bioconductor-illuminahumanmethylation450kanno.ilmn12.hg19: ``>=0.6.0,<0.7.0``
   :depends bioconductor-illuminahumanmethylationepicanno.ilm10b4.hg19: ``>=0.6.0,<0.7.0``
   :depends bioconductor-rtracklayer: ``>=1.50.0,<1.51.0``
   :depends curl: ``>=7.76.0,<8.0a0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-plyr: 
   :depends r-readxl: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-dmrcatedata

   and update with::

      conda update bioconductor-dmrcatedata

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-dmrcatedata:<tag>

   (see `bioconductor-dmrcatedata/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-dmrcatedata| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-dmrcatedata.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-dmrcatedata
   :alt:   (downloads)
.. |docker_bioconductor-dmrcatedata| image:: https://quay.io/repository/biocontainers/bioconductor-dmrcatedata/status
   :target: https://quay.io/repository/biocontainers/bioconductor-dmrcatedata
.. _`bioconductor-dmrcatedata/tags`: https://quay.io/repository/biocontainers/bioconductor-dmrcatedata?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-dmrcatedata/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-dmrcatedata/README.html