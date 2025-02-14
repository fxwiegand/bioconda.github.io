:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-rgreat'
.. highlight: bash

bioconductor-rgreat
===================

.. conda:recipe:: bioconductor-rgreat
   :replaces_section_title:
   :noindex:

   Client for GREAT Analysis

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/rGREAT.html
   :license: MIT + file LICENSE
   :recipe: /`bioconductor-rgreat <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rgreat>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-rgreat/meta.yaml>`_
   :links: biotools: :biotools:`rgreat`, doi: :doi:`10.1038/nmeth.3252`

   This package makes GREAT \(Genomic Regions Enrichment of Annotations Tool\) analysis automatic by constructing a HTTP POST request according to user\'s input and automatically retrieving results from GREAT web server.


.. conda:package:: bioconductor-rgreat

   |downloads_bioconductor-rgreat| |docker_bioconductor-rgreat|

   :versions:
      
      

      ``1.22.0-1``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-1``,  ``1.14.0-0``,  ``1.12.1-0``,  ``1.11.1-0``,  ``1.8.0-0``

      

   
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-getoptlong: ``>=0.0.9``
   :depends r-rcurl: 
   :depends r-rjson: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-rgreat

   and update with::

      conda update bioconductor-rgreat

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-rgreat:<tag>

   (see `bioconductor-rgreat/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-rgreat| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-rgreat.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-rgreat
   :alt:   (downloads)
.. |docker_bioconductor-rgreat| image:: https://quay.io/repository/biocontainers/bioconductor-rgreat/status
   :target: https://quay.io/repository/biocontainers/bioconductor-rgreat
.. _`bioconductor-rgreat/tags`: https://quay.io/repository/biocontainers/bioconductor-rgreat?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-rgreat/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-rgreat/README.html