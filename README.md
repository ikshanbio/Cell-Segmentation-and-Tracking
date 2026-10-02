## Project Name
An Integrated Cell Segmentation and Tracking Pipeline.

## Description
This project allows for the segmentation of time-series images, mostly from live-cell imaging setups, using cellpose segmentation models, which produces segmented object masks for the cells. 
The masks are then tracked across the image series, using btrack, for their positions, genealogy, area among other features. 
The project could be useful for live-cell imaging studies observing genealogy and movement statistics of different cell types.

In case of live-cell imaging of time-dependent fluorophores, channel data for the specific fluorophores can be used to determine the time duration statistics of specific processes, such as cell cycle dynamics. 
(The code was originally developed to extract data-relating to detect dynamics of specific cell cycle proteins).

Developed by Ikshan Ganpathi, at the lab of Prof. Sandip Kar, Department of Chemistry, IIT-Bombay. (https://www.tsbl-skar.com)

## Installation
```bash
git clone https://github.com/ikshanbio/Cell-Segmentation-and-Tracking
cd Cell-Segmentation-and-Tracking
```

## Dependency Acknowledgements 
This project uses:
- [btrack](https://github.com/quantumjot/btrack) (MIT License) — for tracking
- [cellpose](https://github.com/MouseLand/cellpose) (BSD-3-Clause License) — for segmentation

## Citation for cellpose: 
Stringer, C., Wang, T., Michaelos, M. et al. Cellpose: a generalist algorithm for cellular segmentation. Nat Methods 18, 100–106 (2021). https://doi.org/10.1038/s41592-020-01018-x 

## License 
This project is licensed under the GPLv3 License.
