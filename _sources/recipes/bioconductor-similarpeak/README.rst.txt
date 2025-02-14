:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-similarpeak'
.. highlight: bash

bioconductor-similarpeak
========================

.. conda:recipe:: bioconductor-similarpeak
   :replaces_section_title:
   :noindex:

   Metrics to estimate a level of similarity between two ChIP\-Seq profiles

   :homepage: https://bioconductor.org/packages/3.12/bioc/html/similaRpeak.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-similarpeak <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-similarpeak>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-similarpeak/meta.yaml>`_
   :links: biotools: :biotools:`similarpeak`, doi: :doi:`10.1371/journal.pcbi.1004751`

   This package calculates metrics which assign a level of similarity between ChIP\-Seq profiles.


.. conda:package:: bioconductor-similarpeak

   |downloads_bioconductor-similarpeak| |docker_bioconductor-similarpeak|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.22.0-1</code>,  <code>1.22.0-0</code>,  <code>1.20.0-0</code>,  <code>1.18.0-0</code>,  <code>1.16.0-1</code>,  <code>1.16.0-0</code>,  <code>1.14.0-0</code>,  <code>1.12.0-0</code>,  <code>1.10.0-0</code>,  </span></summary>
      

      ``1.22.0-1``,  ``1.22.0-0``,  ``1.20.0-0``,  ``1.18.0-0``,  ``1.16.0-1``,  ``1.16.0-0``,  ``1.14.0-0``,  ``1.12.0-0``,  ``1.10.0-0``,  ``1.8.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-r6: ``>=2.0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-similarpeak

   and update with::

      conda update bioconductor-similarpeak

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-similarpeak:<tag>

   (see `bioconductor-similarpeak/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-similarpeak| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-similarpeak.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-similarpeak
   :alt:   (downloads)
.. |docker_bioconductor-similarpeak| image:: https://quay.io/repository/biocontainers/bioconductor-similarpeak/status
   :target: https://quay.io/repository/biocontainers/bioconductor-similarpeak
.. _`bioconductor-similarpeak/tags`: https://quay.io/repository/biocontainers/bioconductor-similarpeak?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-similarpeak/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-similarpeak/README.html