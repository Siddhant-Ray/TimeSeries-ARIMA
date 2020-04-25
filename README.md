# TimeSeries-ARIMA
An implementation of an ARIMA time series forecast using Python statsmodels and scipy.

Due to a compatibility issue with current version of statsmodels, the scipy module will need to be at version 1.12.1 and the statsmodels at version 0.10.0, instead of version 1.4.1 and 0.11.0 respectively. This can be done in a single step by running the following commands.

$ pip3 uninstall statsmodels <br>
$ pip3 install statsmodels==0.10.0rc2 --pre --user


Installation instructions for Jupyter:

1. Run "pip install notebook" in your shell provided Python is added to path.
2. Run "jupyter notebook" in the required directory.
3. Open the web-based notebook, preferably on Google Chrome.

Running instructions:

1. Run each cell in the notebook with shift+enter.
