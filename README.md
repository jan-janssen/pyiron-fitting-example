# Potential Fitting with pyiron 
While DFT is in principle exact it is limited by the cubic scaling with the number of atoms. Therefore we use DFT calculation to parametrize an interatomic potential which scales linearly with the number of atoms and then us this potential to calculate larger structures which can not be computed with DFT. 

## Step 1: 
To become familiar with recommend the first three exercises from the pyiron video course: 
* [Atomistic structures](https://pyiron.org/phasediagram-workshop-2020/Exercise1.html)
* [Simulation Codes](https://pyiron.org/phasediagram-workshop-2020/Exercise2.html)
* [Density Functional Theory](https://pyiron.org/phasediagram-workshop-2020/Exercise3.html)

## Step 2: 
In this session we are going to use the DFT results calculated in the previous session to fit a Lennard Jones potential: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jan-janssen/pyiron-fitting-example/HEAD?filepath=fit_lennard_jones.ipynb)

## Step 3: 
After the potential is fitted we can compare it to other potentials. For example: 
* [Calculate thermal expansion](https://pyiron.readthedocs.io/en/latest/source/notebooks/first_steps.html) 
* [Calculate thermodynamic properties](https://pyiron.org/phasediagram-workshop-2020/Exercise4.html) 
