:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'pegasusio'
.. highlight: bash

pegasusio
=========

.. conda:recipe:: pegasusio
   :replaces_section_title:
   :noindex:

   PegasusIO is the IO package for Pegasus.

   :homepage: https://github.com/klarman-cell-observatory/pegasusio
   :documentation: https://pegasusio.readthedocs.io
   
   :license: BSD
   :recipe: /`pegasusio <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pegasusio>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/pegasusio/meta.yaml>`_

   


.. conda:package:: pegasusio

   |downloads_pegasusio| |docker_pegasusio|

   :versions:
      
      

      ``0.2.10-1``,  ``0.2.10-0``,  ``0.2.9-0``,  ``0.2.8.post2-0``

      

   
   :depends anndata: ``>=0.7``
   :depends docopt: 
   :depends importlib_metadata: ``>=0.7``
   :depends libgcc-ng: ``>=9.3.0``
   :depends loompy: 
   :depends natsort: 
   :depends numpy: 
   :depends pandas: 
   :depends python: ``>=3.6,<3.7.0a0``
   :depends python_abi: ``3.6.* *_cp36m``
   :depends scipy: 
   :depends zarr: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install pegasusio

   and update with::

      conda update pegasusio

   or use the docker container::

      docker pull quay.io/biocontainers/pegasusio:<tag>

   (see `pegasusio/tags`_ for valid values for ``<tag>``)


.. |downloads_pegasusio| image:: https://img.shields.io/conda/dn/bioconda/pegasusio.svg?style=flat
   :target: https://anaconda.org/bioconda/pegasusio
   :alt:   (downloads)
.. |docker_pegasusio| image:: https://quay.io/repository/biocontainers/pegasusio/status
   :target: https://quay.io/repository/biocontainers/pegasusio
.. _`pegasusio/tags`: https://quay.io/repository/biocontainers/pegasusio?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/pegasusio/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/pegasusio/README.html