---
title: WP2
---

{% import "macros.html" as macros %}


## Coupling between geophysical, RS and water-energy balance model

The value of geophysical datasets (**D1.1** and **D1.2**) lies in their integration within a physical model to establish the connection between geophysical measurements and water pathways within the **Ecologically Critical Zone (ECZ)**. The theoretical foundation of **WP2**’s deliverables centers on deepening our understanding of **soil-moisture-plant interactions** through the application and refinement of the **Soil Water Balance (SWB) model (D2.2)**.

This model not only characterizes **soil states** (e.g., soil water potential *ψ<sub>soil</sub>*, soil moisture *θ<sub>soil</sub>*) but also parameterizes **soil properties** (such as hydraulic conductivity *K<sub>s</sub>* and porosity) and **plant properties** (e.g., leaf water potential, stomatal conductance). By assessing their respective influences on water pathway processes, the model provides a comprehensive framework for analyzing these interactions.

Additionally, the model incorporates **petrophysical relationships** to translate physical measurements (**D2.1**) into meaningful proxies. These relationships are crucial for offering stakeholders **actionable metrics** for forest management, including practices like mulching.

At both the **trial field** and **catchment scales**, **evapotranspiration (ET) quantification** will be achieved using **thermal-based energy balance models**, specifically **Surface Energy Balance (SEB) models** powered by **Land Surface Temperature (LST)** data. High-resolution LST data will be obtained through **image sharpening techniques** (Guzinski et al., 2023). The **SWB model (CATHY)** will be implemented and calibrated using **Earth Observation (EO) satellite data**, either to refine model parameters or update state variables whenever new observations are available. The model will operate continuously, with an **EO data assimilation scheme** to characterize subsoil properties.

Simultaneously, **calibration of the SWB model using ground geophysical measurements** will involve integrating geophysical data into SEB models. This process will address temporal data gaps and enhance the model’s accuracy.

**WP2** is expected to contribute to **Goal 2** by providing:
- Improved estimates of **green water footprint (ET<sub>green</sub>)**
- Enhanced predictions of **groundwater flow and recharge**
- Advanced **water supply forecasts (D2.3)**


---

{{ macros.figure(src="../images/TSEB_multiwater.png", 
    alt="TSEB_multiwater.png", 
    caption="TSEB/3SEB model at the core of GRwater information products output production (Burchard Levine et al., 2021)", 
    figsize="width:70%; height:auto;") }}



{{ macros.figure(src="../images/IDAEA_figs.png", alt="IDAEA_figs.png", caption="Conceptual model of a coupled surface-subsurface hydrology model and its integration within a DA and machine learning scheme to assimilate ground based measurements (geophysical tomography), plant and atmospheric measurements from RS. The soil parameters model is calibrated during an infiltration event or directly
from time lapse ERT observations. Is(t) represent the partitionning of the rain from the tree canopy and the effect of stemflow, Ks1 to Ks3 are the soil hydraulic conductivities that plays a key role in water infiltration rate and that are unknowns model parameters that are inverted (infered during the DA process), RWU is the Root Water Uptake contributing to water use by the vegetation and transpirated.") }}

<div class="callout">
Our work on this theme: in progress
</div>

