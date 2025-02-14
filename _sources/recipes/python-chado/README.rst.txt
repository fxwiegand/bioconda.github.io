:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'python-chado'
.. highlight: bash

python-chado
============

.. conda:recipe:: python-chado
   :replaces_section_title:
   :noindex:

   A Python library for interacting with Chado database.

   :homepage: https://github.com/galaxy-genome-annotation/python-chado
   :license: MIT / MIT
   :recipe: /`python-chado <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/python-chado>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/python-chado/meta.yaml>`_

   


.. conda:package:: python-chado

   |downloads_python-chado| |docker_python-chado|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>2.3.4-0</code>,  <code>2.3.3-1</code>,  <code>2.3.3-0</code>,  <code>2.3.2-0</code>,  <code>2.3.1-0</code>,  <code>2.3.0-0</code>,  <code>2.2.6-0</code>,  <code>2.2.5-0</code>,  <code>2.2.3-0</code>,  </span></summary>
      

      ``2.3.4-0``,  ``2.3.3-1``,  ``2.3.3-0``,  ``2.3.2-0``,  ``2.3.1-0``,  ``2.3.0-0``,  ``2.2.6-0``,  ``2.2.5-0``,  ``2.2.3-0``,  ``2.2.2-0``,  ``2.2.1-0``,  ``2.1.5-0``,  ``2.1.4-0``,  ``2.1.3-1``,  ``2.1.2-1``,  ``2.1.1-0``,  ``2.1-0``,  ``2.0.1-0``,  ``2.0-0``,  ``1.2-0``

      
      .. raw:: html

         </details>
      

   
   :depends bcbio-gff: ``0.6.4``
   :depends biopython: 
   :depends click: 
   :depends future: 
   :depends psycopg2: 
   :depends python: 
   :depends pyyaml: 
   :depends sqlalchemy: 
   :depends wrapt: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install python-chado

   and update with::

      conda update python-chado

   or use the docker container::

      docker pull quay.io/biocontainers/python-chado:<tag>

   (see `python-chado/tags`_ for valid values for ``<tag>``)


.. |downloads_python-chado| image:: https://img.shields.io/conda/dn/bioconda/python-chado.svg?style=flat
   :target: https://anaconda.org/bioconda/python-chado
   :alt:   (downloads)
.. |docker_python-chado| image:: https://quay.io/repository/biocontainers/python-chado/status
   :target: https://quay.io/repository/biocontainers/python-chado
.. _`python-chado/tags`: https://quay.io/repository/biocontainers/python-chado?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/python-chado/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/python-chado/README.html