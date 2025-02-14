:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'debarcer'
.. highlight: bash

debarcer
========

.. conda:recipe:: debarcer
   :replaces_section_title:
   :noindex:

   A package for De\-Barcoding and Error Correction of sequencing data containing molecular barcodes.

   :homepage: https://github.com/oicr-gsi/debarcer
   :license: MIT
   :recipe: /`debarcer <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/debarcer>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/debarcer/meta.yaml>`_

   


.. conda:package:: debarcer

   |downloads_debarcer| |docker_debarcer|

   :versions:
      
      

      ``2.1.3-0``,  ``2.1.1-0``

      

   
   :depends matplotlib-base: ``>=3.1``
   :depends mistune: ``>=0.8``
   :depends networkx: ``>=1.11``
   :depends numpy: ``>=1.14``
   :depends pandas: ``>=0.22``
   :depends pygal: ``>=2.4``
   :depends pysam: ``>=0.14``
   :depends python: ``>=3.6``
   :depends pyyaml: ``>=5.1``
   :depends scipy: ``>=1.0``
   :depends seaborn: ``>=0.9``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install debarcer

   and update with::

      conda update debarcer

   or use the docker container::

      docker pull quay.io/biocontainers/debarcer:<tag>

   (see `debarcer/tags`_ for valid values for ``<tag>``)


.. |downloads_debarcer| image:: https://img.shields.io/conda/dn/bioconda/debarcer.svg?style=flat
   :target: https://anaconda.org/bioconda/debarcer
   :alt:   (downloads)
.. |docker_debarcer| image:: https://quay.io/repository/biocontainers/debarcer/status
   :target: https://quay.io/repository/biocontainers/debarcer
.. _`debarcer/tags`: https://quay.io/repository/biocontainers/debarcer?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/debarcer/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/debarcer/README.html