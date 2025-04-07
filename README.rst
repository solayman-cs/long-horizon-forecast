Long Horizon Forecasting
===========
- Model: LightGBM, Chronos, TimeGPT and TimesFM 


Installation
---------------

Make sure `conda <https://www.anaconda.com/>`_ is installed.


.. code-block:: bash
    # Clone the repo
    git clone https://github.com/solayman-cs/long-horizon-forecast.git
    cd long-horizon-forecast/

.. code-block:: bash
    # Create environment
    conda create --name long_horizon python=3.11.0 

.. code-block:: bash
   # Activate the environment 
   conda activate long_horizon

.. code-block:: bash
   # Install dependencies
    pip install -r requirements.txt

.. code-block:: bash
    pip install ipykernel 
	
.. code-block:: bash
   # Attach environment into jupyter notebook
    python -m ipykernel install --user --name  long_horizon --display-name "long_horizon" 

