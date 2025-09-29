# Bulk solution energy of a solute (pyiron_workflow)
This repository demonstrates computing the bulk solution energy of a substitutional solute in a host lattice using the `pyiron_workflow` framework. The workflow is engine-agnostic and is demonstrated here with LAMMPS.

## Installation
Create and activate the conda environment from the provided `environment.yml`:

```bash
# Using mamba (recommended)
mamba env create -f environment.yml -n pyiron-workflow-bulk-solution
conda activate pyiron-workflow-bulk-solution

# Or using conda
conda env create -f environment.yml -n pyiron-workflow-bulk-solution
conda activate pyiron-workflow-bulk-solution

# To update an existing environment after changes to environment.yml
mamba env update -f environment.yml -n pyiron-workflow-bulk-solution
# or
conda env update -f environment.yml -n pyiron-workflow-bulk-solution
```

## Run the workflow
Open and execute the notebook `bulk_solution_energy.ipynb` in this directory:

```bash
jupyter lab
# or
jupyter notebook
```

Then open `bulk_solution_energy.ipynb` and run all cells.