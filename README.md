# snyk-tensorflow
## Analyze tensorflow dependencies using Synk

Tensorflow builds their pip packages just like everyone else, one [setup.py](https://github.com/tensorflow/tensorflow/blob/1202dd4730cbc9a213f5f039e5bff3ec2e214306/tensorflow/tools/pip_package/setup.py) at a time, however since Tensorflow does not list its Python dependencies in a `requirements.txt` file, Snyk cannot perform its analysis. As a solution, this repository contains the missing requirements file. 
