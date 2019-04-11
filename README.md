# OpenFOAM-Files

Various OpenFOAM scripts and dictionaries.
Generic scripts meant to provide a starting point. Change as needed.

## OpenFOAM and ParaView Cluster Installation (No root access): [OpenFoam_ParaView_Cluster_Installation](/OpenFoam_ParaView_Cluster_Installation/)

Commands to get OpenFOAM and Paraview compiled and running on a HPC (cluster) running on CentOS without root (sudo) access.
Tested on Northumbria University's Oswald Cluster.

## OpenFOAM Parallel Run Commands: [OF_Commands_Parallel](/OF_Commands_Parallel/)

A set of commands to run a parallel generic case in OpenFOAM.
Modify as needed before use.

## OpenFOAM Serial Run Commands: [OF_Commands_Serial](/OF_Commands_Serial/)

A set of commands to run a serial generic case in OpenFOAM.
Modify as needed before use.

## Generic Case Structure: [gen_case_ahmed](/gen_case_ahmed/)

A generic case structure (for an Ahmed Body) to get started (modify as needed before use).
Contains;
- [Residual plots](/gen_case_ahmed/residuals)
- [Coefficient plots](/gen_case_ahmed/plot_coeffs_runtime)
- [Force plots](/gen_case_ahmed/plot_forces_runtime)
- Runtime processing(check [controldict](/gen_case_ahmed/system/controlDict))

*Note: Mesh is very coarse.*

These files have been modified to some extent from case files obtained via tutorials by [Wolfdynamics](http://www.wolfdynamics.com/).

## OpenFOAM Generic Job Submission Scripts (SLURM): [slurm](/slurm/)

A generic job submission scripts for OpenFOAM jobs in a HPC with automated decomposeParDict editing for number of decomposition processors.
