# Simulation of a Positron-Induced Muon Source
<img src=https://indico.cern.ch/event/801616/logo-243447992.png border="0"/> 

### Prerequisites
Python versions used and supported:

[![](https://img.shields.io/badge/python-3.7-blue.svg)](https://badge.fury.io/py/root_pandas)


###  Description and Results
Through a Monte Carlo simulation we study the kinematic features of a low emittance muon beams from e+ e- collisions at centre-of-mass energy just above the μ+ μ- production threshold corresponding to a positron beam of about 45 GeV. 

At the end we obtain the hits distribution in the detector plane and the momenta distributions in the laboratory frame for (anti-)muons.
Regarding of modeling we assumed a positron beam in which particles are uniform distribuited in a circle and with energies gaussian distributed. 
An angular smearing is also considered for each particle composing the incident beam. For the taghet we cosider a 6 cm thick Beryllium block and to obtain the hits distribution for μ+ and μ- we assume the presence of  a  2  meter long,  1.7  Tesla dipole magnet placed after the target. 

All the parameters set in the simulation are easily editable.

### Authors:

- [Alberto Chimenti](https://github.com/albchim) (University of Padova)
- [Clara Eminente](https://github.com/ceminente) (University of Padova)
- [Matteo Guida](https://github.com/matteoguida) (University of Padova)

### Supervised by:

- Professor [Marco Zanetti](https://github.com/mzanetti79) (University of Padova, CERN)
- Camilla Curatolo (University of Padova, INFN)

## Useful External Links:

1. [LEMMA](https://arxiv.org/pdf/1509.04454.pdf), the original paper describing the positron-induced low emittance muon source, here all the relevant kinematic features of the process have been studied
2. [Babayaga](https://www2.pv.infn.it/~hepcomplex/babayaga.html) Monte Carlo event generator for processes at flavour factories. It is used in our simulation for the comparison of the results obtained.
3. Main theoretical source : 

    3.1. [Michael E. Peskin, Dan V. Schroeder - An Introduction to Quantum Field Theory](https://www.amazon.it/Introduction-Quantum-Field-Theory/dp/0201503972/ref=sr_1_1?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=An+Introduction+To+Quantum+Field+Theory&qid=1574948510&sr=8-1).

    3.2. [S Y Lee - Accelerator Physics](https://www.worldscientific.com/worldscibooks/10.1142/8335).
  
4. Doane's formula for binning histograms. [Doane DP (1976) Aesthetic frequency classification](https://amstat.tandfonline.com/doi/abs/10.1080/00031305.1976.10479172#.Xd_N8nVKhNw)
