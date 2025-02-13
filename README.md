# OCMF (Ocean Colour Modelling Framework)
This program is used to illustrate the Ocean Colour Modelling Framework (OCMF) proposed in Sun, Brewin et al. (2025, https://doi.org/10.1016/j.rse.2024.114487) for estimating remote sensing reflectance (Rrs) from chlorophyll-a concentration (Chl-a) and sea surface temperature (SST), building on the classical Case-1 assumption.

OCMF assumes that each phytoplankton size group exists in a distinct optical environment, with specific inherent optical properties (IOPs) assigned to each group. These IOPs are influenced both directly by phytoplankton and indirectly by non-algal particles and dissolved substances. SST is also incorporated as a key factor affecting the composition of phytoplankton size classes (Sun et al., 2023, https://doi.org/10.1016/j.rse.2022.113415, https://github.com/XuerongSun/Three-component-models.git).

Using a large global dataset of optical properties, the OCMF is parameterized, validated, and assessed. It includes absorption (by phytoplankton, non-algal particles, and CDOM) and backscattering (by phytoplankton and non-algal particles), both of which respond to changes in Chl-a and SST. The framework integrates the absorption and backscattering coefficients for each water constituent, also accounting for the influence of non-algal particles on ocean optics.

The notebook can be run through a webpage, just click on the launch-binder image.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/XuerongSun/Ocean-Colour-Modelling-Framework.git/HEAD)
