---
layout: default
title: "Useful Total Scattering Data Processing Utilities"
date: 2025-06-02
status: "completed"
tags: ["data reduction", "advanced"]
---

We are announcing several useful implementations regarding the neutron powder total scattering data reduction and processing.

## Main FeaturesN

- User definition of sample and container geometry for absorption correction enabled in the Mantid framework
- A chunk-by-chunk Fourier filter routine pystog_ck made available to general users on Analysis cluster. Detailed instructions can be found [here](https://powder.ornl.gov/data_tools/general.html).
- A hydrogen background removal routine is available on Analysis through `mts_data`. Detailed instructions can be found [here](https://powder.ornl.gov/data_tools/general.html#mts_data).