# OpenFOAM Generic Job Submission Scripts (SLURM): [slurm](/slurm/)

A generic job submission scripts for OpenFOAM jobs in a HPC with automated decomposeParDict editing for number of decomposition processors.

## Generic SLURM script: [slurm_gen_run](/slurm/slurm_gen_run)

A generic job submission scripts for OpenFOAM jobs (complete run) in a HPC. Sections such as mesh, post-process, reconstruction, etc. need to be configured as needed.

*Note: Generates a casename.foam file for post processing on seperate visual node*

## Generic SLURM Post Processing Script: [slurm_postproc](/slurm/slurm_postproc)

A generic job submission scripts for OpenFOAM post processing. The post processing functions needed must be edited/added accordingly.