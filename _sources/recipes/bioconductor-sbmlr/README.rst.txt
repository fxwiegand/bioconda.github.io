:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-sbmlr'
.. highlight: bash

bioconductor-sbmlr
==================

.. conda:recipe:: bioconductor-sbmlr
   :replaces_section_title:
   :noindex:

   SBML\-R Interface and Analysis Tools

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/SBMLR.html
   :license: GPL-2
   :recipe: /`bioconductor-sbmlr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sbmlr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-sbmlr/meta.yaml>`_

   This package contains a systems biology markup language \(SBML\) interface to R.


.. conda:package:: bioconductor-sbmlr

   |downloads_bioconductor-sbmlr| |docker_bioconductor-sbmlr|

   :versions:
      
      

      ``1.86.0-1``,  ``1.86.0-0``,  ``1.84.0-0``,  ``1.82.0-0``,  ``1.80.0-1``,  ``1.80.0-0``,  ``1.78.0-0``

      

   
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-desolve: 
   :depends r-xml: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-sbmlr

   and update with::

      conda update bioconductor-sbmlr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-sbmlr:<tag>

   (see `bioconductor-sbmlr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-sbmlr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-sbmlr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-sbmlr
   :alt:   (downloads)
.. |docker_bioconductor-sbmlr| image:: https://quay.io/repository/biocontainers/bioconductor-sbmlr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-sbmlr
.. _`bioconductor-sbmlr/tags`: https://quay.io/repository/biocontainers/bioconductor-sbmlr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-sbmlr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-sbmlr/README.html