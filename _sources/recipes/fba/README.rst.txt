:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'fba'
.. highlight: bash

fba
===

.. conda:recipe:: fba
   :replaces_section_title:
   :noindex:

   Tools for feature barcoding analyses

   :homepage: https://github.com/jlduan/fba
   :license: MIT / MIT
   :recipe: /`fba <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/fba>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/fba/meta.yaml>`_

   


.. conda:package:: fba

   |downloads_fba| |docker_fba|

   :versions:
      
      

      ``0.0.10.post1-0``

      

   
   :depends dnaio: 
   :depends hdbscan: ``>=0.8.21``
   :depends matplotlib-base: ``>=3.3``
   :depends numpy: ``>=1.19.0``
   :depends pandas: ``>=1.0.0``
   :depends polyleven: ``>=0.5``
   :depends pyclustering: ``>=0.10.1``
   :depends pysam: ``>=0.14.0``
   :depends python: ``>=3.6``
   :depends regex: 
   :depends scikit-learn: ``>=0.23.0``
   :depends scipy: ``>=1.5.0``
   :depends seaborn: ``>=0.10.0``
   :depends statsmodels: ``>=0.11.1``
   :depends umap-learn: 
   :depends umi_tools: ``>=1.0.0``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install fba

   and update with::

      conda update fba

   or use the docker container::

      docker pull quay.io/biocontainers/fba:<tag>

   (see `fba/tags`_ for valid values for ``<tag>``)


.. |downloads_fba| image:: https://img.shields.io/conda/dn/bioconda/fba.svg?style=flat
   :target: https://anaconda.org/bioconda/fba
   :alt:   (downloads)
.. |docker_fba| image:: https://quay.io/repository/biocontainers/fba/status
   :target: https://quay.io/repository/biocontainers/fba
.. _`fba/tags`: https://quay.io/repository/biocontainers/fba?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/fba/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/fba/README.html