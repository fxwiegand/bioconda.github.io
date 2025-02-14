:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'gtdbtk'
.. highlight: bash

gtdbtk
======

.. conda:recipe:: gtdbtk
   :replaces_section_title:
   :noindex:

   A toolkit for assigning objective taxonomic classifications to bacterial and archaeal genomes.

   :homepage: https://github.com/Ecogenomics/GTDBTk
   :license: GPL3 / GNU General Public v3 (GPLv3)
   :recipe: /`gtdbtk <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gtdbtk>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/gtdbtk/meta.yaml>`_
   :links: doi: :doi:`10.1093/bioinformatics/btz848`

   


.. conda:package:: gtdbtk

   |downloads_gtdbtk| |docker_gtdbtk|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>1.4.1-1</code>,  <code>1.4.1-0</code>,  <code>1.4.0-1</code>,  <code>1.4.0-0</code>,  <code>1.3.0-2</code>,  <code>1.3.0-1</code>,  <code>1.3.0-0</code>,  <code>1.2.0-1</code>,  <code>1.2.0-0</code>,  </span></summary>
      

      ``1.4.1-1``,  ``1.4.1-0``,  ``1.4.0-1``,  ``1.4.0-0``,  ``1.3.0-2``,  ``1.3.0-1``,  ``1.3.0-0``,  ``1.2.0-1``,  ``1.2.0-0``,  ``1.1.1-0``,  ``1.1.0-0``,  ``1.0.2-3``,  ``1.0.2-2``,  ``1.0.2-1``,  ``1.0.2-0``,  ``1.0.1-1``,  ``1.0.1-0``,  ``1.0.0-0``,  ``0.3.3-0``,  ``0.3.2-2``,  ``0.3.2-1``,  ``0.3.2-0``,  ``0.3.1-0``,  ``0.3.0-1``,  ``0.3.0-0``,  ``0.2.2-0``,  ``0.1.6-0``,  ``0.1.5-0``,  ``0.1.3-0``

      
      .. raw:: html

         </details>
      

   
   :depends dendropy: ``>=4.1.0``
   :depends fastani: ``>=1.32``
   :depends fasttree: ``>=2.1.9``
   :depends hmmer: ``3.1b2``
   :depends mash: ``>=2.0``
   :depends numpy: ``>=1.9.0``
   :depends pplacer: ``>=1.1.alpha17``
   :depends prodigal: ``>=2.6.2``
   :depends python: ``>=3.6``
   :depends tqdm: ``>=4.31.0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install gtdbtk

   and update with::

      conda update gtdbtk

   or use the docker container::

      docker pull quay.io/biocontainers/gtdbtk:<tag>

   (see `gtdbtk/tags`_ for valid values for ``<tag>``)


.. |downloads_gtdbtk| image:: https://img.shields.io/conda/dn/bioconda/gtdbtk.svg?style=flat
   :target: https://anaconda.org/bioconda/gtdbtk
   :alt:   (downloads)
.. |docker_gtdbtk| image:: https://quay.io/repository/biocontainers/gtdbtk/status
   :target: https://quay.io/repository/biocontainers/gtdbtk
.. _`gtdbtk/tags`: https://quay.io/repository/biocontainers/gtdbtk?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/gtdbtk/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/gtdbtk/README.html