# Computational Optogenetics : Validation and Inference of light Diffusion (COVID)
## Master 2 project by Louis Eparvier, in collaboration with Hugo Ladret & Samuel Bélanger, supervised by Matthieu Vanni

## Description of the project
The aim of this project is to measure the functional diffusion of opsin-dependant activity in the mouse cortex. We will combine Monte-Carlo simulation of light diffusion with cortical spiking network simulations.
 
## Progress tracker 
### Monte-Carlo 
* [] Upload script and ouput matrices
### Spiking Network
* [x] Extract morphology from swc files
* [x] Reconstruct cortical morphology from [this paper](https://www.biorxiv.org/content/10.1101/662189v2.full.pdf) and [this file](https://www.dropbox.com/sh/w5u31m3hq6u2x5m/AAD34a7F63f7nRYUq2vLR3sha/build_model/column_structure.xlsx?dl=0)
* [x] Create opsin-based currents with Brian
* [x] Create population-level opsin currents

## Some figures
A single layer of the model 
![Cannot display correctly image](https://github.com/hugoladret/covid/blob/master/figs/onelayer.png)

Multiple layers of the model 
![Cannot display correctly image](https://github.com/hugoladret/covid/blob/master/figs/all_layers.png)
