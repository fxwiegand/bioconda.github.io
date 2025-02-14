:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'abpoa'
.. highlight: bash

abpoa
=====

.. conda:recipe:: abpoa
   :replaces_section_title:
   :noindex:

   abPOA\: fast SIMD\-based partial order alignment using adaptive band

   :homepage: https://github.com/yangao07/abPOA
   :license: GPL
   :recipe: /`abpoa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/abpoa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/abpoa/meta.yaml>`_

   


.. conda:package:: abpoa

   |downloads_abpoa| |docker_abpoa|

   :versions:
      
      

      ``1.1.0-1``,  ``1.1.0-0``,  ``1.0.6-0``,  ``1.0.5-0``,  ``1.0.4-0``,  ``1.0.3-0``,  ``1.0.2-0``,  ``1.0.1-0``,  ``1.0.0-0``

      

   
   :depends libgcc-ng: ``>=9.3.0``
   :depends zlib: ``>=1.2.11,<1.3.0a0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install abpoa

   and update with::

      conda update abpoa

   or use the docker container::

      docker pull quay.io/biocontainers/abpoa:<tag>

   (see `abpoa/tags`_ for valid values for ``<tag>``)


.. |downloads_abpoa| image:: https://img.shields.io/conda/dn/bioconda/abpoa.svg?style=flat
   :target: https://anaconda.org/bioconda/abpoa
   :alt:   (downloads)
.. |docker_abpoa| image:: https://quay.io/repository/biocontainers/abpoa/status
   :target: https://quay.io/repository/biocontainers/abpoa
.. _`abpoa/tags`: https://quay.io/repository/biocontainers/abpoa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/abpoa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/abpoa/README.html