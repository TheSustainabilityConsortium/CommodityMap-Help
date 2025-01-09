---
layout: default
title: Data Release Notes
parent: Data Sources
nav_order: 2
description: "Data Release Notes"
---

# Data Release Notes

## January Crop Production Data Update
Released January 9, 2025

### Dataset Updates
* Updated the USDA Cropland Data Layer (CDL) from 2022 to 2023
* Updated MapSPAM from 2010 to 2020

### Manual Changes
* Changed mapspam_dataset codes in app_supported_commodities and cached_scores for arabica (from 'coff' back to 'acof' and small millet (from 'mill' back to 'smil') so that users with existing analyses of these commodities would be able to refresh them using the standard instructions for updates.
* Updated mapspam_dataset codes in user analyses so that they could also be updated using the standard instructions (e.g., updating an oranges analysis from pointing to 'trof' to 'citr').

### More Info
* See the <a href="https://sustainabilityconsortium.org/commoditymap-january-2025-data-update/?utm_source=CMHelp&utm_medium=help+link&utm_campaign=Jan25DataUpdate">blog post</a>.