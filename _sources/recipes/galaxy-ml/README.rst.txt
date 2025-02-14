:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'galaxy-ml'
.. highlight: bash

galaxy-ml
=========

.. conda:recipe:: galaxy-ml
   :replaces_section_title:
   :noindex:

   APIs for Galaxy machine learning tools

   :homepage: https://github.com/goeckslab/Galaxy-ML
   :license: MIT
   :recipe: /`galaxy-ml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/galaxy-ml>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/galaxy-ml/meta.yaml>`_

   


.. conda:package:: galaxy-ml

   |downloads_galaxy-ml| |docker_galaxy-ml|

   :versions:
      
      
      .. raw:: html

         <details><summary><span class="truncated-version-list"><code>0.8.3-2</code>,  <code>0.8.3-1</code>,  <code>0.8.3-0</code>,  <code>0.8.2-5</code>,  <code>0.8.2-4</code>,  <code>0.8.2-3</code>,  <code>0.8.2-2</code>,  <code>0.8.2-1</code>,  <code>0.8.2-0</code>,  </span></summary>
      

      ``0.8.3-2``,  ``0.8.3-1``,  ``0.8.3-0``,  ``0.8.2-5``,  ``0.8.2-4``,  ``0.8.2-3``,  ``0.8.2-2``,  ``0.8.2-1``,  ``0.8.2-0``,  ``0.8.1-0``,  ``0.8.0-0``,  ``0.7.12-0``,  ``0.7.11-0``,  ``0.7.10-1``,  ``0.7.10-0``,  ``0.7.9-0``,  ``0.7.8-0``,  ``0.7.7-1``,  ``0.7.7-0``,  ``0.7.5-0``,  ``0.7.4.1-0``

      
      .. raw:: html

         </details>
      

   
   :depends asteval: ``>=0.9``
   :depends graphviz: ``>=2.38``
   :depends h5py: ``>=2.10.0,<3.0``
   :depends htslib: 
   :depends imbalanced-learn: ``<0.6``
   :depends joblib: 
   :depends keras: ``2.3.1``
   :depends libgcc-ng: ``>=9.3.0``
   :depends libstdcxx-ng: ``>=9.3.0``
   :depends matplotlib-base: 
   :depends mlxtend: ``<0.18``
   :depends numpy: ``>=1.17.0,<1.19``
   :depends pandas: ``<0.26``
   :depends pillow: ``>=6.0``
   :depends plotly: ``4.3``
   :depends psutil: ``>=5.6``
   :depends pydot: ``>=1.4``
   :depends pyfaidx: 
   :depends pytabix: 
   :depends python: ``>=3.6,<3.7.0a0``
   :depends python_abi: ``3.6.* *_cp36m``
   :depends readme_renderer: ``>=24.0``
   :depends requests: ``>=2.22.0``
   :depends scikit-learn: ``0.21.3``
   :depends scikit-optimize: ``>=0.7,<0.8``
   :depends scipy: ``>=1.3``
   :depends skrebate: ``<0.7``
   :depends tensorflow: ``>=1.15.0,<2.0``
   :depends tensorflow-estimator: ``1.15.1``
   :depends xgboost: ``<=0.80``
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install galaxy-ml

   and update with::

      conda update galaxy-ml

   or use the docker container::

      docker pull quay.io/biocontainers/galaxy-ml:<tag>

   (see `galaxy-ml/tags`_ for valid values for ``<tag>``)


.. |downloads_galaxy-ml| image:: https://img.shields.io/conda/dn/bioconda/galaxy-ml.svg?style=flat
   :target: https://anaconda.org/bioconda/galaxy-ml
   :alt:   (downloads)
.. |docker_galaxy-ml| image:: https://quay.io/repository/biocontainers/galaxy-ml/status
   :target: https://quay.io/repository/biocontainers/galaxy-ml
.. _`galaxy-ml/tags`: https://quay.io/repository/biocontainers/galaxy-ml?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/galaxy-ml/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/galaxy-ml/README.html