# CyVerse Visual Interactive Computing Environment

Welcome to the CyVerse VICE, where we keep our docker images for use in the [Discovery Environment](https://de.cyverse.org) data science workbench. 
(Get it? a workbench, a VICE...)

We maintain these repositories with continuous integration. The containers should be auto-rebuilt every week and then pushed to our public/private container registry.

# Featured Images
```{bash}
. docker://harbor.cyverse.org/vice/ 
├── cli/bash:latest - Cloud Shell
├── jupyter/datascience:latest - Project Jupyter Lab DataScience
│        ├── /earthlab:latest 
│        ├── /geospatial:latest
│        └── /QIIME2:2022.8
├── jupyter/pytorch:latest - Project Jupyter Lab Pytorch
│        └── /cudagl-22.04 
├── jupyter/tensorflow:latest - Project Jupyter Lab Tensorflow
│        └── /cudagl-22.04
├── rstudio/verse:latest - Rocker RStudio Verse
│        └── /geospatial:latest 
│              ├── /stan:latest
│              └── /ecocompdp:latest 
├── xpra/desktop:22.04 - NVIDIA OpenGL Ubuntu 22.04
│   └──Xpra Desktop 22.04
│        ├── /cellprofiler:22.04 - Cell Profiler 
│        ├── /cloudcompare:22.04 - CloudCompare
│        └── /qgis: 22.04 - QGIS/GRASS/SAGA-GIS
├── xpra/cudagl:22.04 - NVIDIA CUDA OpenGL Ubuntu 22.04
│        ├── /cellprofiler:22.04 Cell Profiler 
│        ├── /cloudcompare:22.04 CloudCompare
│        └── /qgis:22.04 QGIS/GRASS/SAGA-GIS
└── vscode:latest - VS Code 
```
