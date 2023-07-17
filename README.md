# Cherian, Guo, & Bryan (2023)

This repo contains code to reproduce images for the paper in `paper-figures.ipynb`.

Subsets of data for the NATRE region are saved in `datasets/`

We are exploring approaches to provide more useful fields. 

The current subsets should prove useful for comparisons in the NATRE region.

For an idea of how the subset were produced see `dataset-processing.ipynb`

## Datasets
| Filename                       | Description                                                                                                      |
|--------------------------------|------------------------------------------------------------------------------------------------------------------|
| `cole-clim-gradient-natre.nc`  | time mean conservative temperature and absolute salinity in $σ$ Space                                            |
| `cole-natre.nc`                | Cole et al (2015) dataset subset to NATRE region                                                                 |
| `ecco-climatology-natre.nc`    | Mean over ECCO simulation period of GM-Redi χ terms and state variables.                                         |
| `groeskamp-natre.nc`           | Groeskamp et al (2020) dataset subset to NATRE region                                                            |
| `natre-density-binned.nc`      | NATRE microstructure data processed to yield estimates in neutral density bins following Ferrari & Polzin (2005) |
| `pop-1-month1.nc`              | POP 1° mean profile in NATRE region for first month of simulation                                                |
| `pop-1-spinup-natre.nc`        | POP 1° mean profile in NATRE region as decadal means for the first cycle (or 60 years) of simulation             |
| `pop-110-climatology-natre.nc` | POP 1/10° mean state variables                                                                                   |
| `pop-110-variance-natre.nc`    | POP1/10° variance budget terms from Guo et al (2022)                                                             |
