:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'r-acidbase'
.. highlight: bash

r-acidbase
==========

.. conda:recipe:: r-acidbase
   :replaces_section_title:
   :noindex:

   Low\-level base functions imported by Acid Genomics packages.

   :homepage: https://r.acidgenomics.com/packages/acidbase/
   :developer docs: https://github.com/acidgenomics/r-acidbase
   :license: GPL / AGPL-3.0
   :recipe: /`r-acidbase <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-acidbase>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/r-acidbase/meta.yaml>`_

   


.. conda:package:: r-acidbase

   |downloads_r-acidbase| |docker_r-acidbase|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.3.13-1</code>,  <code>0.3.13-0</code>,  <code>0.2.6-1</code>,  <code>0.2.6-0</code>,  <code>0.2.5-0</code>,  <code>0.2.4-0</code>,  <code>0.2.3-0</code>,  <code>0.1.14-0</code>,  <code>0.1.13-0</code>,  </span></summary>
      

      ``0.3.13-1``,  ``0.3.13-0``,  ``0.2.6-1``,  ``0.2.6-0``,  ``0.2.5-0``,  ``0.2.4-0``,  ``0.2.3-0``,  ``0.1.14-0``,  ``0.1.13-0``,  ``0.1.12-0``,  ``0.1.11-0``,  ``0.1.10-0``,  ``0.1.9-1``,  ``0.1.9-0``,  ``0.1.8-1``,  ``0.1.8-0``,  ``0.1.7-0``,  ``0.1.6-0``,  ``0.1.5-0``,  ``0.1.4-0``,  ``0.1.3-0``,  ``0.1.2-0``,  ``0.1.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends r-acidcli: ``>=0.1.0``
   :depends r-acidgenerics: ``>=0.5.17``
   :depends r-base: ``>=4.0,<4.1.0a0``
   :depends r-goalie: ``>=0.5.0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install r-acidbase

   and update with::

      conda update r-acidbase

   or use the docker container::

      docker pull quay.io/biocontainers/r-acidbase:<tag>

   (see `r-acidbase/tags`_ for valid values for ``<tag>``)


.. |downloads_r-acidbase| image:: https://img.shields.io/conda/dn/bioconda/r-acidbase.svg?style=flat
   :target: https://anaconda.org/bioconda/r-acidbase
   :alt:   (downloads)
.. |docker_r-acidbase| image:: https://quay.io/repository/biocontainers/r-acidbase/status
   :target: https://quay.io/repository/biocontainers/r-acidbase
.. _`r-acidbase/tags`: https://quay.io/repository/biocontainers/r-acidbase?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/r-acidbase/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/r-acidbase/README.html