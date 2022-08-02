# Field-Stepped Ultra-Wideline NMR

MATLAB GUI for fitting ultra-wideline quadrupolar NMR patterns using field-stepped acquisitions

## Requirements
- All testing has been done on MATLAB 2020a and newer
- The Parrallel Computing Toolbox in MATLAB

## Installation
- MATLAB needs to be installed
- Download the .mlappinstall file and follow the installation instructions

## Features
- Simulate central transition NMR patterns of half-integer quadrupolar nuclei acquired with incremented field strength
- Can simulate any number of evenly-spaced field increments; the simulated increments are attenuated by a window function 
- Two site simulations
- Can include satellite transitions (ST) for common isotope pairs such as 35Cl/37Cl and 79Br/81Br
- Can overlay an experimental spectrum if it is pre-processed as a .mat file 
- spec.mat is a pre-processed spectrum that is included as an example (use a 20 MHz spectral window and 0 Hz offset)

## Citing
If you use the GUI please cite the following:
I. Hung; A.R. Altenhof; R.W. Schurko; D.L. Bryce; O.H. Han; and Z. Gan. Field-stepped ultra-wideline NMR at up to 36 T: On the inequivalence between field and frequency stepping. 
https://doi.org/10.1002/mrc.5128

## Contact
Please contact rschurko@fsu.edu with any quesitons, feedback, or suggestions.

## Creators
- Adam Altenhof
- Ivan Hung
- Zhehong Gan

## Support
This software was supported (in part) by the National Science Foundation Chemical Measurement and Imaging Program, with partial co-funding from the Solid State and Materials Chemistry Program (NSF-2003854).

## License
MIT

[//]: # ()

   [dill]: <https://github.com/joemccann/dillinger>
