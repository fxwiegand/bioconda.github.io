:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'igv'
.. highlight: bash

igv
===

.. conda:recipe:: igv
   :replaces_section_title:
   :noindex:

   Integrative Genomics Viewer. Fast\, efficient\, scalable visualization tool for genomics
   data and annotations.


   :homepage: http://www.broadinstitute.org/software/igv/home
   :license: MIT
   :recipe: /`igv <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/igv>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/igv/meta.yaml>`_
   :links: biotools: :biotools:`igv`

   


.. conda:package:: igv

   |downloads_igv| |docker_igv|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>2.9.4-1</code>,  <code>2.9.4-0</code>,  <code>2.9.3-0</code>,  <code>2.9.2-0</code>,  <code>2.9.1-0</code>,  <code>2.9.0-0</code>,  <code>2.8.13-0</code>,  <code>2.8.12-0</code>,  <code>2.8.11-0</code>,  </span></summary>
      

      ``2.9.4-1``,  ``2.9.4-0``,  ``2.9.3-0``,  ``2.9.2-0``,  ``2.9.1-0``,  ``2.9.0-0``,  ``2.8.13-0``,  ``2.8.12-0``,  ``2.8.11-0``,  ``2.8.10-0``,  ``2.8.9-0``,  ``2.8.8-0``,  ``2.8.6-0``,  ``2.8.5-0``,  ``2.8.4-0``,  ``2.8.3-0``,  ``2.8.2-0``,  ``2.8.1-0``,  ``2.8.0-0``,  ``2.5.2-0``,  ``2.4.17-0``,  ``2.4.16-0``,  ``2.4.9-1``,  ``2.4.9-0``,  ``2.4.6-0``,  ``2.3.98-0``

      
      .. raw:: html

         </details>
      

   
   :depends openjdk: ``>=11``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install igv

   and update with::

      conda update igv

   or use the docker container::

      docker pull quay.io/biocontainers/igv:<tag>

   (see `igv/tags`_ for valid values for ``<tag>``)


.. |downloads_igv| image:: https://img.shields.io/conda/dn/bioconda/igv.svg?style=flat
   :target: https://anaconda.org/bioconda/igv
   :alt:   (downloads)
.. |docker_igv| image:: https://quay.io/repository/biocontainers/igv/status
   :target: https://quay.io/repository/biocontainers/igv
.. _`igv/tags`: https://quay.io/repository/biocontainers/igv?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/igv/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/igv/README.html