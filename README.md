# ENVS-193DS_spring-2025_final
Final for ENVS 193DS

## General information

Datasets from: 

Kui, L. 2024. Daily sea surface temperature in Santa Barbara channel between 1982 and 2023 ver 3. Environmental Data Initiative. https://doi.org/10.6073/pasta/e930954949b2635928b8be6824630f84. 

Stojanovic D, Owens G, Young CM, Alves F, Heinsohn R. 2020. Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird. Restoration Ecology. 29(3). doi:https://doi.org/10.1111/rec.13319.

This repository is for practicing research writing, data visualization, data analysis, and discussing my exploratory and affective visualizations.

# Packages

```
library(tidyverse) # loading packages
library(janitor)
library(here)
library(ggeffects)
library(MuMIn)
library(DHARMa)
```

## Data and file overview

```
├── ENVS-193DS_spring-2025_final.Rproj
├── README.md
├── code                                 
│   ├── final.html            
│   └── final.qmd            
│   
└── data                                     
    ├── occdist.csv
    └── SST_update2023.csv
```

All code is in the `code` folder. The code runs models, generates model predictions, and visualizes data.

## Rendered output

Rendered .html: https://kathrynk04.github.io/ENVS-193DS_spring-2025_final/code/final.html