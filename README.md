# An AO-ADMM approach to constraining PARAFAC2 on all modes
[<img src="https://img.shields.io/badge/doi-10.1137%2F21M1450033-blue" alt="10.1137/21M1450033" />](https://doi.org/10.1137/21M1450033)
[<img src="https://img.shields.io/badge/arXiv-2110.01278-green.svg" alt="arXiv link" />](https://arxiv.org/abs/2110.01278)

This repository contains links to code and simulated data used in the paper [*An AO-ADMM approach to constraining PARAFAC2 on all modes*](https://doi.org/10.1137/21M1450033) published in SIAM Journal on Mathematics of Data Science. The accepted manuscript is available on arXiv at [https://arxiv.org/abs/2110.01278](https://arxiv.org/abs/2110.01278).

## Code

The Python implementation of the PARAFAC2 AO-ADMM scheme developed for this publication is available in the [tensorkit](https://github.com/marieroald/tensorkit)
and [bcd_tensorkit](https://github.com/marieroald/bcd_tensorkit)
 repositories. However, we recommend using [MatCoupLy](https://github.com/marieroald/matcouply), which is an updated implementation with a more user-friendly API and thorough [documentation](https://matcouply.readthedocs.io/). Both implementations project depend on [condat_tv](https://github.com/marieroald/condat_tv)
 for the total variation proximal operator.

The MATLAB implementation for the AO-ADMM algorithm is available in [this repository](https://github.com/AOADMM-DataFusionFramework/AOADMM-PARAFAC2).

For the performance metrics, we used the implementations in [TensorLy-viz](https://tensorly.org/viz).


## Simulated data tensors

The simulated data tensors used for the experiments in the paper is available in the [datasets](datasets/) directory, where each data tensor is stored in
a separate [HDF5](https://www.hdfgroup.org/solutions/hdf5/) file.

See also [this notebook](Simulation_of_components.ipynb) for code to simulate evolving PARAFAC2 components. The notebook is also available as an interactive Binder notebook: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/marieroald/PARAFAC2-AOADMM-SIMODS/HEAD?filepath=Simulation_of_components.ipynb)
