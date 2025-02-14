:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'sourmash'
.. highlight: bash

sourmash
========

.. conda:recipe:: sourmash
   :replaces_section_title:
   :noindex:

   Compute and compare MinHash signatures for DNA data sets.

   :homepage: https://github.com/dib-lab/sourmash
   :documentation: https://sourmash.readthedocs.io/
   
   :license: BSD / BSD-3-Clause
   :recipe: /`sourmash <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sourmash>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/sourmash/meta.yaml>`_
   :links: biotools: :biotools:`sourmash`, doi: :doi:`10.21105/joss.00027`, doi: :doi:`10.12688/f1000research.19675.1`

   


.. conda:package:: sourmash

   |downloads_sourmash| |docker_sourmash|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>4.0.0-2</code>,  <code>4.0.0-1</code>,  <code>4.0.0-0</code>,  <code>3.5.1-0</code>,  <code>3.5.0-0</code>,  <code>3.4.1-0</code>,  <code>3.4.0-0</code>,  <code>3.3.1-0</code>,  <code>3.3.0-1</code>,  </span></summary>
      

      ``4.0.0-2``,  ``4.0.0-1``,  ``4.0.0-0``,  ``3.5.1-0``,  ``3.5.0-0``,  ``3.4.1-0``,  ``3.4.0-0``,  ``3.3.1-0``,  ``3.3.0-1``,  ``3.3.0-0``,  ``3.2.3-0``,  ``3.2.2-1``,  ``3.2.2-0``,  ``3.2.1-1``,  ``3.2.1-0``,  ``3.2.0-0``,  ``3.1.0-0``,  ``3.0.1-0``,  ``3.0.0-0``,  ``2.3.1-0``,  ``2.3.0-0``,  ``2.2.0-1``,  ``2.2.0-0``,  ``2.1.0-0``,  ``2.0.1-0``,  ``2.0.0-1``,  ``2.0.0-0``,  ``2.0.0a11-0``,  ``2.0.0a10-0``,  ``2.0.0a9-0``,  ``2.0.0a8-2``,  ``2.0.0a8-1``,  ``2.0.0a8-0``,  ``2.0.0a7-0``,  ``2.0.0a6-0``,  ``2.0.0a5-0``,  ``2.0.0a4-0``,  ``2.0.0a3-0``,  ``2.0.0a2-0``,  ``2.0.0a1-3``,  ``2.0.0a1-2``,  ``2.0.0a1-1``,  ``2.0.0a1-0``,  ``1.0-0``

      
      .. raw:: html

         </details>
      

   
   :depends matplotlib-base: 
   :depends numpy: 
   :depends python: 
   :depends scipy: 
   :depends sourmash-minimal: ``4.0.0.*``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install sourmash

   and update with::

      conda update sourmash

   or use the docker container::

      docker pull quay.io/biocontainers/sourmash:<tag>

   (see `sourmash/tags`_ for valid values for ``<tag>``)


.. |downloads_sourmash| image:: https://img.shields.io/conda/dn/bioconda/sourmash.svg?style=flat
   :target: https://anaconda.org/bioconda/sourmash
   :alt:   (downloads)
.. |docker_sourmash| image:: https://quay.io/repository/biocontainers/sourmash/status
   :target: https://quay.io/repository/biocontainers/sourmash
.. _`sourmash/tags`: https://quay.io/repository/biocontainers/sourmash?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/sourmash/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/sourmash/README.html