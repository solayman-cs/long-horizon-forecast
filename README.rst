Long Horizon Forecasting
===========
- Model: LightGBM and TimesFM 


Installation
---------------

Make sure `conda <https://www.anaconda.com/>`_ is installed.


.. code-block:: bash

    # clone the repo
    git clone https://github.com/solayman-cs/long-horizon-forecast.git
    cd long-horizon-forecast/

.. code-block:: bash

    # create environment
    conda create --name long_horizon python=3.11.0 
	conda activate long_horizon

.. code-block:: bash

    # install dependencies
    pip install -r requirements.txt

.. code-block:: bash

    # Attach environment into jupyter notebook
    pip install ipykernel 
	python -m ipykernel install --user --name  long_horizon --display-name "long_horizon" 


