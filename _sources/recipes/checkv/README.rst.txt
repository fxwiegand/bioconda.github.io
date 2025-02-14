:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'checkv'
.. highlight: bash

checkv
======

.. conda:recipe:: checkv
   :replaces_section_title:
   :noindex:

   Assess the quality of metagenome\-assembled viral genomes.

   :homepage: https://bitbucket.org/berkeleylab/checkv
   :license: BSD / Modified BSD
   :recipe: /`checkv <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/checkv>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/checkv/meta.yaml>`_

   


.. conda:package:: checkv

   |downloads_checkv| |docker_checkv|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.7.0-1</code>,  <code>0.7.0-0</code>,  <code>0.6.0-1</code>,  <code>0.6.0-0</code>,  <code>0.5.1-1</code>,  <code>0.5.1-0</code>,  <code>0.4.0-1</code>,  <code>0.4.0-0</code>,  <code>0.3.0-0</code>,  </span></summary>
      

      ``0.7.0-1``,  ``0.7.0-0``,  ``0.6.0-1``,  ``0.6.0-0``,  ``0.5.1-1``,  ``0.5.1-0``,  ``0.4.0-1``,  ``0.4.0-0``,  ``0.3.0-0``,  ``0.2.0-0``,  ``0.1.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends biopython: 
   :depends blast: 
   :depends diamond: 
   :depends hmmer: 
   :depends importlib-metadata: ``>=0.12``
   :depends numpy: 
   :depends prodigal: 
   :depends psutil: 
   :depends python: ``>=3.6``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install checkv

   and update with::

      conda update checkv

   or use the docker container::

      docker pull quay.io/biocontainers/checkv:<tag>

   (see `checkv/tags`_ for valid values for ``<tag>``)


.. |downloads_checkv| image:: https://img.shields.io/conda/dn/bioconda/checkv.svg?style=flat
   :target: https://anaconda.org/bioconda/checkv
   :alt:   (downloads)
.. |docker_checkv| image:: https://quay.io/repository/biocontainers/checkv/status
   :target: https://quay.io/repository/biocontainers/checkv
.. _`checkv/tags`: https://quay.io/repository/biocontainers/checkv?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/checkv/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/checkv/README.html