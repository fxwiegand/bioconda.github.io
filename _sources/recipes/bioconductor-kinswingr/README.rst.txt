:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-kinswingr'
.. highlight: bash

bioconductor-kinswingr
======================

.. conda:recipe:: bioconductor-kinswingr
   :replaces_section_title:
   :noindex:

   KinSwingR\: network\-based kinase activity prediction

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/KinSwingR.html
   :license: GPL-3
   :recipe: /`bioconductor-kinswingr <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-kinswingr>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-kinswingr/meta.yaml>`_

   KinSwingR integrates phosphosite data derived from mass\-spectrometry data and kinase\-substrate predictions to predict kinase activity. Several functions allow the user to build PWM models of kinase\-subtrates\, statistically infer PWM\:substrate matches\, and integrate these data to infer kinase activity.


.. conda:package:: bioconductor-kinswingr

   |downloads_bioconductor-kinswingr| |docker_bioconductor-kinswingr|

   :versions:
      
      

      ``1.8.0-1``,  ``1.8.0-0``,  ``1.6.0-0``,  ``1.4.0-0``,  ``1.2.0-1``,  ``1.2.0-0``,  ``1.0.3-0``

      

   
   :depends bioconductor-biocparallel: ``>=1.24.0,<1.25.0``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-data.table: 
   :depends r-sqldf: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-kinswingr

   and update with::

      conda update bioconductor-kinswingr

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-kinswingr:<tag>

   (see `bioconductor-kinswingr/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-kinswingr| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-kinswingr.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-kinswingr
   :alt:   (downloads)
.. |docker_bioconductor-kinswingr| image:: https://quay.io/repository/biocontainers/bioconductor-kinswingr/status
   :target: https://quay.io/repository/biocontainers/bioconductor-kinswingr
.. _`bioconductor-kinswingr/tags`: https://quay.io/repository/biocontainers/bioconductor-kinswingr?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-kinswingr/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-kinswingr/README.html