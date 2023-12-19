# A first-principles model for the Ba-Zr-S system in equilibrium with sulfur vapour

Data and computational notebook for the paper "A first-principles model for the Ba-Zr-S system in equilibrium with sulfur vapour".

The [Jupyter Notebook]() `thermodynamic_analysis.ipynb` can be used to reproduce the results reported in this paper. 
Any other combination of reactants and products listed in the `data` folder can be analysed using a similar sequence of commands.

The analysis depends our open-source Python code [ThermoPot](), which can be [downloaded via pip]().

Data used in the analysis are included in the folder `data`:

  - `nist_janaf`: S2 and S8 thermodynamic data from the [NIST-JANAF thermochemical tables](https://janaf.nist.gov/).
  - `phonopy_output`: thermodynamic data for solid materials, generated using [Phonopy](https://phonopy.github.io/phonopy/).
  - `raw_aims_files`: input and output files for total energy calculations using [FHI-aims](https://fhi-aims.org/). Data generated using a range of functionals: pbe, pbesol, hse06 and scan.
