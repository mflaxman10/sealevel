
## Sea level constrained by observations and commitment

If you make use of this code, please cite

```
Future sea level rise constrained by observations and long-term commitment
M. Mengel et al. PNAS 2016
```
Find the paper here: [http://dx.doi.org/10.1073/pnas.1500515113](http://dx.doi.org/10.1073/pnas.1500515113).

This repository contains the code to produce the results as presented in the paper.
There are two main parts: The calibration of the model and using the model for projections.

### Making projections
See the [projections.ipynb](https://github.com/matthiasmengel/sealevel/blob/master/examples/projection.ipynb) for projections using a sample global temperature mean timeseries.
If you do not have [jupyter](http://jupyter.org/) notebook, [install](http://jupyter.readthedocs.org/en/latest/install.html) it or look at [projection.py](https://github.com/matthiasmengel/sealevel/blob/master/examples/projection.py).

### Recalibrating the model
See [src/do_calibration.py](https://github.com/matthiasmengel/sealevel/blob/master/src/do_calibration.py).
Model calibration is based on data for past thermal expansion, glaciers and ice caps loss and ice sheet evolution, which is not completely openly available. Please contact the M. Mengel or the authors of the datasets applied for calibration if you plan to recalibrate or extend the model.

### Installation

`git clone https://github.com/matthiasmengel/sealevel.git`

`cd sealevel`

then with pip

`pip install requirements.txt`

or with conda

`conda env create -f environment.yml`

The model is written in python. If this is new to you, you may have a look at [anaconda python](https://www.continuum.io/downloads). The code has not been tested for Windows.

### Dependencies

[scipy](http://www.scipy.org/), 
[numpy](http://www.numpy.org/), 
[dimarray](http://dimarray.readthedocs.org/en/latest/), 
[pandas](http://pandas.pydata.org/)
[matplotlib](http://matplotlib.org/) for plotting, 
[jupyter](http://jupyter.org/) for convenience.

See [requirements.txt](https://github.com/matthiasmengel/sealevel/blob/master/requirements.txt) for details.

### Issues and contributing

Please post issues on the [issue tracker](https://github.com/matthiasmengel/sealevel/issues) or contact the author. Contributions or propositions to extend the model are most welcome.

### Versions

v 1.0.0: code as used for the Mengel et al., PNAS 2016, [http://dx.doi.org/10.1073/pnas.1500515113](http://dx.doi.org/10.1073/pnas.1500515113).

### License

This code is licensed under GPLv3, see the LICENSE.txt. It was authored by [Matthias Mengel](http://www.pik-potsdam.de/~mengel/) working at [Potsdam Institute for Climate Impact Research](http://pik-potsdam.de/). 


