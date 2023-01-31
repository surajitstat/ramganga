Resources will be available here
## Recent publications

## Available data

The Indian Institute of Technology Kanpur team are collecting data from 17 sites along the Ramganga river and its tributaries. Satellite data are also being calibrated by the University of Stirling team for use in data fusion.

### Field campaigns

Sampling campaigns are being carried out to catch multiple cycles of data:

| 2019 |  Geochemical data | Sonde instrument | WISP instrument | Biological kit | DNA kit | Drone |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
|       Monsoon (August) | Yes
|       Post-monsoon (December) | Yes
| **2020** |  
|       Monsoon (September) | Yes | Yes 
|       Post-monsoon (December) | Yes | Yes 
| **2021** | 
|       Pre-monsoon (March) | Yes | Yes | Yes | Yes | Yes 
|       Monsoon (TBC) | Yes | Yes | Yes | Yes | Yes | Yes 
|       Post-monsoon (TBC) | Yes | Yes | Yes | Yes | Yes | Yes 

Water samples are collected to be analysed in the laboratory by Inductively coupled plasma mass spectroscopy (ICP-MS) and by Ion Chromatography. Two instruments and two kits provide additional data.

| Geochemical data | | |
| --- | --- | --- |
| Trace elements | 27 elements | by Inductively coupled plasma mass spectroscopy (ICP-MS) |
| Cation | 4 elements | by Ion Chromatography |
| Anions | 6 elements | by Ion Chromatography |
| **Physicochemical and biological data** | | |
| Sonde Instrument | 6 parameters | |
| WISP Instrument | 4 parameters | |
| Biological Kit | 2 parameters | |
| DNA Kit | | Sent to UK Centre for Ecology and Hydrology for analysis |

**Drone images** will also be captured in the monsoon and post-monsoon field campaigns in 2021, capturing short regions of the river at high spatial resolution (approximately 2m by 2m grid).

### Remote sensing data

Sentinel-2 images are being calibrated by the University of Stirling team for use in data fusion. Each image will capture the river on a grid with a high spatial resolution of 10m by 10m. Measures of chlorophyll-a and total suspended matter will be derived from the reflectances.

## Summary results

## Codes/Softwares

The NSD R package for nonparametric statistical downscaling is available on GitHub [here](https://github.com/cwilkie1990/NSD). The package can be installed within R using `devtools::install_github("cwilkie1990/NSD")`. The package contains two main functions:

* `run.NSDmodel()` allows fitting the nonparametric statistical downscaling model of [Wilkie et al. (2019)](https://doi.org/10.1002/env.2549) to fuse data of different spatiotemporal support.
* `run.NSDmodelMulti()` is similar to `run.NSDmodel()`, but with two covariates to be fused with the response rather than the single covariate in `run.NSDmodel()`.

The R package documentation is available as a PDF document here: [NSD.pdf](https://github.com/surajitstat/ramganga/files/10549593/NSD.pdf).

## Shiny App


