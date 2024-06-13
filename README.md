# Courants-Derivants-Cmems

This repo contains 
my Study notebooks on the agestrophic components of currents, for my internship in oceanography.

## Working in your own jupyterlab

At present, there are 5 notebooks and 3 folders available to illustrate:

- **Annexe Folder**: Contains notebooks pertaining to our theme, but with more advanced versions available in the folders CMEMS_notebooks and NOAA_notebooks.

- **CMEMS_notebooks Folder**: Contains 5 notebooks:

    - **Notebook 3**: Interpolates CMEMS data on the spatial and temporal grid of drifting buoys using the linear interpolation method.
    - **Notebook 5**:   Visualisation the inertial oscillation of drifter velocities and wind direction.
    - **Notebook 7-1**: Utilizes Drifter and CMEMS current data to estimate the depth of the Ekman layer and the drag coefficient noted as h_e and r_e respectively.
    - **Notebook 7-2**: Enhances CMEMS currents by adding the Ekman component calculated from NOAA wind data from the product: CoastWatch Caribb-NOAA AOML.
    - **Notebook 7-3**: Repeats the same process as in notebook 7-1, this time using CMEMS wind data.

- **NOAA_notebooks Folder**: Contains 3 notebooks. In this folder, I revisit the topics covered in notebooks 3, 5, and 7 using geostrophic current and wind data provided entirely by NOAA.
- [Drifters and currents](1-dériveurs-courants-visualisations.ipynb)  
We visualize the current variables present in our drifter data. These variables are Eastward velocity (ve), Northward velocity (vn), and we also include the visualization of sea surface temperature (SST) present in our data.
- [Dérivants et positions](2-drifters-positions.ipynb) 
We gather all the drifters present in our datasets and provide their positions within our study area for a selected collection date.
- [Inertial oscillation](4-oscillation-inertielle-des-dérives.ipynb)
After interpolating CMEMS data onto the drifters, we notice that the period of oscillations is much shorter. The question arises: could this be due to inertial waves? From the frequencies derived from these waves, we conclude that it is indeed the inertial wave because the frequencies obtained are on the order of 10^-5, which are of the same magnitude as those corresponding to Coriolis forces and thus potentially inertial forces.
- [Tracjectoire sur les profils de SSH et SST](2-drifters-positions.ipynb) 
In this notebook, we visualize the trajectory of our drifter on the profiles of SSH and SST.
- [Méthodes d'évaluation des courants de surface](Méthodes-de-calcul-des-courants.ipynb)
This notebook aims to detail the methods of calculating ocean currents as presented in the articles by Lagerloef (1999) and Picaut (1990). 




