:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'genewalk'
.. highlight: bash

genewalk
========

.. conda:recipe:: genewalk
   :replaces_section_title:
   :noindex:

   Determine gene function based on network embeddings.

   :homepage: https://github.com/churchmanlab/genewalk
   :documentation: https://genewalk.readthedocs.io/en/latest/
   
   :license: BSD / BSD-2-Clause
   :recipe: /`genewalk <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/genewalk>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/genewalk/meta.yaml>`_

   


.. conda:package:: genewalk

   |downloads_genewalk| |docker_genewalk|

   :versions:
      
      

      ``1.5.2-0``,  ``1.5.1-0``

      

   
   :depends gensim: ``<4.0``
   :depends goatools: 
   :depends matplotlib-base: 
   :depends networkx: ``>=2.1``
   :depends numpy: 
   :depends pandas: 
   :depends plotly: ``>=4.0.0``
   :depends python: 
   :depends scipy: ``>=1.3.0``
   :depends seaborn: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install genewalk

   and update with::

      conda update genewalk

   or use the docker container::

      docker pull quay.io/biocontainers/genewalk:<tag>

   (see `genewalk/tags`_ for valid values for ``<tag>``)


.. |downloads_genewalk| image:: https://img.shields.io/conda/dn/bioconda/genewalk.svg?style=flat
   :target: https://anaconda.org/bioconda/genewalk
   :alt:   (downloads)
.. |docker_genewalk| image:: https://quay.io/repository/biocontainers/genewalk/status
   :target: https://quay.io/repository/biocontainers/genewalk
.. _`genewalk/tags`: https://quay.io/repository/biocontainers/genewalk?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/genewalk/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/genewalk/README.html