:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bellmans-gapc'
.. highlight: bash

bellmans-gapc
=============

.. conda:recipe:: bellmans-gapc
   :replaces_section_title:
   :noindex:

   A language and compiler for algebraic dynamic programming.

   :homepage: https://bibiserv.cebitec.uni-bielefeld.de/gapc
   :license: GPLv3+
   :recipe: /`bellmans-gapc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bellmans-gapc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bellmans-gapc/meta.yaml>`_

   


.. conda:package:: bellmans-gapc

   |downloads_bellmans-gapc| |docker_bellmans-gapc|

   :versions:
      
      

      ``2020.12.08-1``,  ``2020.12.08-0``,  ``2020.07.07-0``,  ``2020.01.08-1``,  ``2020.01.08-0``,  ``0.1-2``,  ``0.1-1``,  ``0.1-0``

      

   
   :depends blas: 
   :depends boost-cpp: ``>=1.74.0,<1.74.1.0a0``
   :depends gsl: ``>=2.6,<2.7.0a0``
   :depends libgcc-ng: ``>=9.3.0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends make: 
   :depends sed: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bellmans-gapc

   and update with::

      conda update bellmans-gapc

   or use the docker container::

      docker pull quay.io/biocontainers/bellmans-gapc:<tag>

   (see `bellmans-gapc/tags`_ for valid values for ``<tag>``)


.. |downloads_bellmans-gapc| image:: https://img.shields.io/conda/dn/bioconda/bellmans-gapc.svg?style=flat
   :target: https://anaconda.org/bioconda/bellmans-gapc
   :alt:   (downloads)
.. |docker_bellmans-gapc| image:: https://quay.io/repository/biocontainers/bellmans-gapc/status
   :target: https://quay.io/repository/biocontainers/bellmans-gapc
.. _`bellmans-gapc/tags`: https://quay.io/repository/biocontainers/bellmans-gapc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bellmans-gapc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bellmans-gapc/README.html