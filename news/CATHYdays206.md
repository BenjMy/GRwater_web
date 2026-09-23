---
title: "Roadmap to water accounting at catchment scale using hydrogeophysics and DA | Benjamin Mary (ICA-CSIC) at CATHY Days 2026"
date: 2026-07-03
---

{% import "macros.html" as macros %}

At [CATHY Days 2026](https://cathy-org.github.io/CATHY_days_2026/) in Modena (July 3rd, 2026), [Benjamin Mary](../team#Benjamin Mary) (ICA-CSIC) presented a talk titled **"Roadmap to water accounting at catchment scale using hydrogeophysics and DA"**, focusing on integrated hydrological modeling, remote sensing, and geophysical data assimilation using `pyCATHY`[cite: 1]. During the event, participants also had the opportunity to visit the local observatory tower.

{{ macros.figure(src="../images/news/cathy2026/CATHYdays_participants.jpg", alt="CATHY Days 2026 participants group photo", caption="Participants of CATHY Days 2026 gathered in Modena.", figsize="width: 60%; display: block; margin-left: auto; margin-right: auto;") }}

## Presentation Overview

The presentation highlighted key advancements and workflows within `pyCATHY`, an open-source, FAIR wrapper for the CATHY hydrological model[cite: 1]:

- **CATHY & EO Modules:** Integrating CATHY core (Fortran) with Earth Observation (EO) data such as pyTSEB for evapotranspiration modeling, netCDF raster handling, and post-fire catchment recovery applications (e.g., GRWATER project)[cite: 1].
- **Geophysics & DA Modules:** Coupling hydrological simulations with geophysical tools (pyGIMLi, EMagPy) for 3D soil characterization, electrical resistivity tomography (ERT), and data assimilation (EnKF) using actual and synthetic observations (ERT, $ET_a$)[cite: 1].
- **Current Bottlenecks & Future Perspectives:** Addressing challenges in observation covariance matrices and filter inbreeding, alongside future developments for agricultural water accounting (Centum algorithm, blue vs. green water footprint) and AI integration[cite: 1].

{{ macros.figure(src="../images/news/cathy2026/ModenaTower.jpg", alt="Modena observatory tower", caption="Visit to the observatory tower during CATHY Days 2026.", figsize="width: 60%; display: block; margin-left: auto; margin-right: auto;") }}

> **How to cite / Learn more:** Mary, B., et al. pyCATHY wrapper repository: https://github.com/BenjMy/pycathy_wrapper[cite: 1].