:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-reportingtools'
.. highlight: bash

bioconductor-reportingtools
===========================

.. conda:recipe:: bioconductor-reportingtools
   :replaces_section_title:
   :noindex:

   Tools for making reports in various formats

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/ReportingTools.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-reportingtools <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-reportingtools>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-reportingtools/meta.yaml>`_
   :links: biotools: :biotools:`reportingtools`

   The ReportingTools software package enables users to easily display reports of analysis results generated from sources such as microarray and sequencing data.  The package allows users to create HTML pages that may be viewed on a web browser such as Safari\, or in other formats readable by programs such as Excel.  Users can generate tables with sortable and filterable columns\, make and display plots\, and link table entries to other data sources such as NCBI or larger plots within the HTML page.  Using the package\, users can also produce a table of contents page to link various reports together for a particular project that can be viewed in a web browser.  For more examples\, please visit our site\: http\:\/\/ research\-pub.gene.com\/ReportingTools.


.. conda:package:: bioconductor-reportingtools

   |downloads_bioconductor-reportingtools| |docker_bioconductor-reportingtools|

   :versions:
      
      

      ``2.30.2-0``,  ``2.30.0-0``,  ``2.28.0-0``,  ``2.26.0-0``,  ``2.24.0-1``,  ``2.22.1-0``,  ``2.22.0-0``,  ``2.20.0-0``,  ``2.17.3-0``

      

   
   :depends bioconductor-annotate: ``>=1.68.0,<1.69.0``
   :depends bioconductor-annotationdbi: ``>=1.52.0,<1.53.0``
   :depends bioconductor-biobase: ``>=2.50.0,<2.51.0``
   :depends bioconductor-biocgenerics: ``>=0.36.0,<0.37.0``
   :depends bioconductor-category: ``>=2.56.0,<2.57.0``
   :depends bioconductor-deseq2: ``>=1.30.0,<1.31.0``
   :depends bioconductor-edger: ``>=3.32.0,<3.33.0``
   :depends bioconductor-ggbio: ``>=1.38.0,<1.39.0``
   :depends bioconductor-gostats: ``>=2.56.0,<2.57.0``
   :depends bioconductor-gseabase: ``>=1.52.0,<1.53.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-limma: ``>=3.46.0,<3.47.0``
   :depends bioconductor-pfam.db: ``>=3.12.0,<3.13.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-ggplot2: 
   :depends r-hwriter: 
   :depends r-knitr: 
   :depends r-lattice: 
   :depends r-r.utils: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-reportingtools

   and update with::

      conda update bioconductor-reportingtools

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-reportingtools:<tag>

   (see `bioconductor-reportingtools/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-reportingtools| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-reportingtools.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-reportingtools
   :alt:   (downloads)
.. |docker_bioconductor-reportingtools| image:: https://quay.io/repository/biocontainers/bioconductor-reportingtools/status
   :target: https://quay.io/repository/biocontainers/bioconductor-reportingtools
.. _`bioconductor-reportingtools/tags`: https://quay.io/repository/biocontainers/bioconductor-reportingtools?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-reportingtools/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-reportingtools/README.html