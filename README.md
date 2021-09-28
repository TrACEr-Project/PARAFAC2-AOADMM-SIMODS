# An AO-ADMM approach to constraining PARAFAC2 on all modes


## Code

The Python implementation developed as part of this project is available on the [tensorkit](https://github.com/marieroald/tensorkit)
and [bcd_tensorkit](https://github.com/marieroald/bcd_tensorkit) repositories. The project also depends on [condat_tv](https://github.com/marieroald/condat_tv)
for the total variation proximal operator.

The MATLAB implementation for the AO-ADMM algorithm is available in [this repository](https://github.com/AOADMM-DataFusionFramework/AOADMM-PARAFAC2).

For the performance metrics, we used the implementations in [this repository](https://github.com/marieroald/component-vis).


## Simulated data tensors

The simulated data tensors used for the experiments in the paper is available in the [datasets](datasets/) directory, where each data tensor is stored in
a separate [HDF5](https://www.hdfgroup.org/solutions/hdf5/) file.

See also [this notebook](Simulation_of_components.ipynb) for code to simulate evolving PARAFAC2 components. The notebook is also available as an interactive Binder notebook: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/marieroald/PARAFAC2-AOADMM-SIMODS/HEAD?filepath=Simulation_of_components.ipynb)
