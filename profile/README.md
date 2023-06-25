# CyVerse Visual Interactive Computing Environment

Welcome to the CyVerse VICE, where we keep our docker images for use in the [Discovery Environment](https://de.cyverse.org) data science workbench. 
(Get it? a workbench, a VICE...)

We maintain these repositories with continuous integration. The containers should be auto-rebuilt every week and then pushed to our public/private container registry.

# Featured Images
```{bash}
. docker://harbor.cyverse.org/vice/ 
├── cli - Cloud Shell
│    ├── /bash:latest 
│    └── /zsh:latest 
├── jupyter/datascience - Project Jupyter Lab DataScience
│        ├── /earthlab:latest 
│        ├── /geospatial:latest
│        └── /QIIME2:2022.8
├── jupyter/pytorch - Project Jupyter Lab Pytorch
│        └── /cudagl-22.04:latest 
├── jupyter/tensorflow - Project Jupyter Lab Tensorflow
│        └── /cudagl-22.04:latest
├── rstudio/verse - Rocker RStudio Verse
│        └── /geospatial:latest 
│              ├── /stan:latest
│              └── /ecocompdp:latest 
├── xpra/cudagl - NVIDIA CUDA OpenGL Ubuntu 22.04
│        ├── /cellprofiler:22.04 Cell Profiler 
│        ├── /cloudcompare:22.04 CloudCompare
│        └── /qgis:22.04 QGIS/GRASS/SAGA-GIS
├── xpra/desktop - NVIDIA OpenGL Ubuntu 22.04
│        ├── /cellprofiler:22.04 
│        ├── /cloudcompare:22.04 
│        └── /qgis: 22.04
└── vscode - VS Code 
     └── :latest 
```
