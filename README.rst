Long Horizon Forecasting
===========
- Model: LightGBM, Chronos, TimeGPT and TimesFM 


Installation
---------------

Make sure `conda <https://www.anaconda.com/>`_ is installed.

### Clone the repo
.. code-block:: bash

    git clone https://github.com/solayman-cs/long-horizon-forecast.git
    cd long-horizon-forecast/

### Create environment
.. code-block:: bash

    conda create --name long_horizon python=3.11.0 

### Activate the environment 	
.. code-block:: bash

   conda activate long_horizon

### Install dependencies
.. code-block:: bash

    pip install -r requirements.txt

### Attach environment into `jupyter` notebook
.. code-block:: bash

    pip install ipykernel 
	
.. code-block:: bash

    python -m ipykernel install --user --name  long_horizon --display-name "long_horizon" 

