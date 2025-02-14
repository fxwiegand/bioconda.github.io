:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-anvilpublish'
.. highlight: bash

bioconductor-anvilpublish
=========================

.. conda:recipe:: bioconductor-anvilpublish
   :replaces_section_title:
   :noindex:

   Publish Packages and Other Resources to AnVIL Workspaces

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/AnVILPublish.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-anvilpublish <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-anvilpublish>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-anvilpublish/meta.yaml>`_

   Use this package to create or update AnVIL workspaces from resources such as R \/ Bioconductor packages. The metadata about the package \(e.g.\, select information from the package DESCRIPTION file and from vignette YAML headings\) are used to populate the \'DASHBOARD\'. Vignettes are translated to python notebooks ready for evaluation in AnVIL.


.. conda:package:: bioconductor-anvilpublish

   |downloads_bioconductor-anvilpublish| |docker_bioconductor-anvilpublish|

   :versions:
      
      

      ``1.0.0-3``,  ``1.0.0-2``

      

   
   :depends bioconductor-anvil: ``>=1.2.0,<1.3.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-httr: 
   :depends r-rmarkdown: 
   :depends r-whisker: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-anvilpublish

   and update with::

      conda update bioconductor-anvilpublish

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-anvilpublish:<tag>

   (see `bioconductor-anvilpublish/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-anvilpublish| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-anvilpublish.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-anvilpublish
   :alt:   (downloads)
.. |docker_bioconductor-anvilpublish| image:: https://quay.io/repository/biocontainers/bioconductor-anvilpublish/status
   :target: https://quay.io/repository/biocontainers/bioconductor-anvilpublish
.. _`bioconductor-anvilpublish/tags`: https://quay.io/repository/biocontainers/bioconductor-anvilpublish?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-anvilpublish/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-anvilpublish/README.html