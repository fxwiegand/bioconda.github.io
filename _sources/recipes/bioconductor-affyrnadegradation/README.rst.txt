:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-affyrnadegradation'
.. highlight: bash

bioconductor-affyrnadegradation
===============================

.. conda:recipe:: bioconductor-affyrnadegradation
   :replaces_section_title:
   :noindex:

   Analyze and correct probe positional bias in microarray data due to RNA degradation

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/AffyRNADegradation.html
   :license: GPL-2
   :recipe: /`bioconductor-affyrnadegradation <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affyrnadegradation>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-affyrnadegradation/meta.yaml>`_
   :links: biotools: :biotools:`affyrnadegradation`

   The package helps with the assessment and correction of RNA degradation effects in Affymetrix 3\' expression arrays. The parameter d gives a robust and accurate measure of RNA integrity. The correction removes the probe positional bias\, and thus improves comparability of samples that are affected by RNA degradation.


.. conda:package:: bioconductor-affyrnadegradation

   |downloads_bioconductor-affyrnadegradation| |docker_bioconductor-affyrnadegradation|

   :versions:
      
      

      ``1.36.0-1``,  ``1.36.0-0``,  ``1.34.0-0``,  ``1.32.0-0``,  ``1.30.0-1``,  ``1.28.0-0``,  ``1.26.0-0``,  ``1.24.0-0``,  ``1.22.0-0``

      

   
   :depends bioconductor-affy: ``>=1.68.0,<1.69.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-affyrnadegradation

   and update with::

      conda update bioconductor-affyrnadegradation

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-affyrnadegradation:<tag>

   (see `bioconductor-affyrnadegradation/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-affyrnadegradation| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-affyrnadegradation.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-affyrnadegradation
   :alt:   (downloads)
.. |docker_bioconductor-affyrnadegradation| image:: https://quay.io/repository/biocontainers/bioconductor-affyrnadegradation/status
   :target: https://quay.io/repository/biocontainers/bioconductor-affyrnadegradation
.. _`bioconductor-affyrnadegradation/tags`: https://quay.io/repository/biocontainers/bioconductor-affyrnadegradation?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-affyrnadegradation/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-affyrnadegradation/README.html