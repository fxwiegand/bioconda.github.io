:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tracktables'
.. highlight: bash

bioconductor-tracktables
========================

.. conda:recipe:: bioconductor-tracktables
   :replaces_section_title:
   :noindex:

   Build IGV tracks and HTML reports

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/tracktables.html
   :license: GPL (>= 3)
   :recipe: /`bioconductor-tracktables <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tracktables>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tracktables/meta.yaml>`_
   :links: biotools: :biotools:`tracktables`, doi: :doi:`10.1038/nmeth.3252`

   Methods to create complex IGV genome browser sessions and dynamic IGV reports in HTML pages.


.. conda:package:: bioconductor-tracktables

   |downloads_bioconductor-tracktables| |docker_bioconductor-tracktables|

   :versions:
      
      

      ``1.24.0-1``,  ``1.24.0-0``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``

      

   
   :depends bioconductor-genomicranges: ``>=1.42.0,<1.43.0``
   :depends bioconductor-iranges: ``>=2.24.0,<2.25.0``
   :depends bioconductor-rsamtools: ``>=2.6.0,<2.7.0``
   :depends bioconductor-xvector: ``>=0.30.0,<0.31.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-rcolorbrewer: 
   :depends r-stringr: 
   :depends r-tractor.base: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tracktables

   and update with::

      conda update bioconductor-tracktables

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tracktables:<tag>

   (see `bioconductor-tracktables/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tracktables| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tracktables.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tracktables
   :alt:   (downloads)
.. |docker_bioconductor-tracktables| image:: https://quay.io/repository/biocontainers/bioconductor-tracktables/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tracktables
.. _`bioconductor-tracktables/tags`: https://quay.io/repository/biocontainers/bioconductor-tracktables?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tracktables/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tracktables/README.html