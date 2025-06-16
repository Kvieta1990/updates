---
layout: default
title: "Updates on Absorption Pre-Calculation"
date: 2025-06-16
status: "completed"
tags: ["data reduction", "caching", "performance"]
---

We just added in the beamn height definition in the absorption pre-calculation routine (`abs_pre_calc`) for SNS powder diffractometers at ORNL. Meanwhile, the routine now incorporate the autoreduction configuration routine so that all necessary operations to be done regarding the autoreduction can be done with a single routine,

- Sample information collection

- Absorption pre-calculation

- Autoreduction configuration