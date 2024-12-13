# MODFLOW-Project
This project was completed in 2021.
## MODFLOW2000 Project

### Overview

**MODFLOW2000** is a widely used, modular groundwater flow model developed by the United States Geological Survey (USGS). It provides a numerical simulation framework for evaluating groundwater flow in both confined and unconfined aquifers. The software uses a finite-difference approach to solve the groundwater flow equation, allowing for the simulation of complex hydrogeological conditions.

This project employs MODFLOW2000 to assess the impacts of different agricultural and water management practices on groundwater resources in a specified region. The analysis aims to understand the dynamics of groundwater recharge, water table decline, and the overall sustainability of aquifer systems under varying scenarios.

### Data Requirements

The MODFLOW2000 model requires the following datasets for setup and simulation:

#### Spatial Data

1.**Aquifer Properties**:

* Hydraulic conductivity (K)

* Specific yield (Sy)

* Storage coefficient (Ss)

2.**Topography and Boundaries**:

* Digital elevation model (DEM) for defining the model grid.

* Boundary conditions (e.g., no-flow, constant-head, or general-head boundaries).

#### Hydrological Data

* Recharge rates from precipitation and irrigation.

* Groundwater abstraction rates (e.g., pumping well data).

* Streamflow interactions for coupled surface and groundwater systems.

* Initial water table elevations.

#### Climate Data (Optional)

* Precipitation and evapotranspiration data for calculating recharge.

### Project Highlights

In this project, MODFLOW2000 was used to:

* Simulate groundwater flow patterns under different water management practices.

* Assess the impact of agricultural irrigation on aquifer sustainability.

* Evaluated the effect of groundwater withdrawal on water table variations under agricultural irrigation scenarios.

* Demonstrated the utility of MODFLOW2000 for sustainable groundwater resource planning.

### How to Use

1.**Prepare the Input Files**:

* Define the model grid and aquifer properties.

* Set boundary and initial conditions.

* Include stress data, such as recharge and pumping schedules.

2.**Run the Model**:

* Use the MODFLOW2000 executable or a compatible interface such as GMS (Groundwater Modeling System).

* Simulate steady-state or transient conditions based on the objectives.

3. **Analyze the Results**:

* Visualize outputs such as water table elevation, water table decline, and flow paths using post-processing tools.

* Compare scenarios to evaluate the impact of different practices.

### Visualization

Although no specific map is included in this repository, results such as water table contours and water table decline maps can be visualized using GIS software or dedicated groundwater modeling tools like ModelMuse. Additionally, project-related images and visualizations can be found in this [article](https://link.springer.com/article/10.1007/s12665-023-10824-3).

### Access the Model

The complete MODFLOW2000 model files can be accessed here [Unsteady State](https://drive.google.com/file/d/1EFVDZLF57ToSNo7O74yvDIgAALQKi295/view?usp=drive_link)|[Steady State](https://drive.google.com/file/d/1sXAesRlLd0sUAzXCzuIjJSCD1vzB9G1N/view?usp=drive_link). 
### References

Harbaugh, A. W., et al. (2000). "MODFLOW-2000, the US Geological Survey Modular Ground-Water Model." USGS Open-File Report 00-92.

[Official MODFLOW Website](https://www.usgs.gov/mission-areas/water-resources/science/modflow-and-related-programs) for additional resources and tools.
