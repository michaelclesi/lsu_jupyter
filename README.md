This is a customized version of Open OnDemand's Jupyter application for LSU HPC's mike cluster.

This version launches a 'master module' that loads several machine learning kernels and users own personal kernels.

To use own kernel, users must run `conda install ipykernel` in their activated conda environments.

Current implementation handles custom logic for single and gpu queues (gpu core count scales by gpus).


