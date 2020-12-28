# Tidal model of the Spermonde Archipelago
This repository contains the results of a DELFT 3D model run, that simulates tides in the Spermonde Archipelago from Jan 1 2017 to Jan 1 2019. The model was set up with Delft Dashboard, following the tutorial at this link: https://www.youtube.com/watch?v=t3grdR4rYVY

A detailed description of Delft Dashboard can be found here:
> van Ormondt, M., Nederhoff, K. and van Dongeren, A., 2020. Delft Dashboard: a quick set-up tool for hydrodynamic models. Journal of Hydroinformatics, 22(3), pp.510-527.

## Model files
The model files (DELFT 3D model files and resulting NEFIS map file) are available via ZENODO: 
The NEFIS files can be opened via QuickPlot (DELFT 3D) or OpenEarthTools. The Zenodo repository also contains a \*.mat file exported with QuickPlot, that can be opened with Matlab or Octave. 

## Model boundary conditions
Boundary conditions were derived from astronomic forcing from the TPXO 7.2 Global Inverse tide model, described here:

> Egbert, Gary D., and Svetlana Y. Erofeeva. "Efficient inverse modeling of barotropic ocean tides." Journal of Atmospheric and Oceanic Technology 19.2 (2002): 183-204.

Bathymetric data were downloaded from GEBCO:

> GEBCO Compilation Group (2020) GEBCO 2020 Grid (doi:10.5285/a29c5465-b138-234d-e053-6c86abc040b9)

The model has a grid size of 2x2km, and covers the extent of the Spermonde Archipelago. The following image shows the gridded bathymetry for the tidal model, and validation sites.
 
<img src="Tide_model_Spermonde/Validation/Model_overview.png" width="50%" height="50%">

## Validation
The model was validated in two ways. First, we used the IHO database built into Delft Dashboard and compred it with our modeled data for the entire simulation time. The result is shown in the figure below.

