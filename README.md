# jupyter-workflows

Repository containing example ```jupyter``` workflows illustrating the integration of different processes and programs with ```python```.

### List of workflows

- ```ex_sgsim_uncond_modflow```: Generates an unconditional Gaussian simulation with ```geostatspy``` to create a synthetic two-dimensional aquifer with heterogeneous hydraulic conductivity. Groundwater flow is simulated with MODFLOW 6 and ```flopy```, and the streamlines are calculated with MODPATH 7. This workflow allows to evaluate the impact of different geostatistics on the flow streamlines. 

- ```ex_sgsim_uncond_modflow_rw```: Generates an unconditional Gaussian simulation with ```geostatspy``` to create a synthetic two-dimensional aquifer with heterogeneous hydraulic conductivity. Groundwater flow is steady, simulated with MODFLOW 6 and ```flopy```, and the streamlines are calculated with MODPATH 7. This workflow simulates the transport of an initial injection of a pollutant, solving solute transport with MODPATH-RW and ```flopyrw```. The workflow enables the interpretation of the influence of the geostatistics on the fate of a contaminant plume. 



## Resources
* [flopy](https://github.com/modflowpy/flopy)
* [flopyrw](https://github.com/upc-ghs/flopyrw)
* [MODPATH-RW](https://github.com/upc-ghs/modpath-rw)
* [modflow 6](https://github.com/MODFLOW-USGS/modflow6)
* [modflow executables](https://github.com/MODFLOW-USGS/executables)
* [modpath-v7](https://github.com/MODFLOW-USGS/modpath-v7)
* [modpath-omp](https://github.com/upc-ghs/modpath-omp)
* [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy)
* [GSLIB executables](https://github.com/upc-ghs/gslib-executables)
