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

# create environment
.. code-block:: bash
    conda create --name long_horizon python=3.11.0 

# activate the environment 	
.. code-block:: bash
   conda activate long_horizon

# install dependencies
.. code-block:: bash
    pip install -r requirements.txt

# Attach environment into jupyter notebook
.. code-block:: bash
    pip install ipykernel 
	
.. code-block:: bash
    python -m ipykernel install --user --name  long_horizon --display-name "long_horizon" 

