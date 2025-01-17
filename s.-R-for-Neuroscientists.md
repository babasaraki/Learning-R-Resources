<link href="https://fonts.googleapis.com/css?family=Cookie" rel="stylesheet"><a class="bmc-button" target="_blank" href="https://www.buymeacoffee.com/JoscelinRocha"><img src="https://cdn.buymeacoffee.com/buttons/bmc-new-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:5px;font-size:28px !important;">Buy me a coffee</span></a> or Venmo me (@JoscelinRocha)   ​

***
# fNIRS & NIRS
## [erzk/fnirsr: Package for analysing funtional near-infrared spectroscopy (fNIRS) data](https://rdrr.io/github/erzk/fnirsr/#vignettes)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: Load, slice, filter, plot, and transform fNIRS data. The majority of functions were developed to work with Hitachi ETG-4000 data.

Link to repo here: https://github.com/erzk/fnirsr
     
Cool functions from package:         

1. **load_ETG4000_data()**: Loading the signal from csv files
1. **plot_ETG4000()**: Plotting function with "facets" as default. 
1. **remove_channels_ETG4000()**: If a channel (or several channels) is corrupt and cannot be cleaned then the simplest way to obtain clean grand average is to remove the noisy channel.
1. **detrend_ETG4000_data()**: fNIRS signal is likely to show a linear trend which can be removed. Grand Average in the plot above is showing a linear downward trend. The linear trend can be removed from all channels (recommended) or from a single channel.


## [NIRStat: Novel Statistical Methods for Studying Near-Infrared Spectroscopy (NIRS) Time Series Data](https://cran.r-project.org/web/packages/NIRStat/index.html)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: Provides transfusion-related differential tests on Near-infrared spectroscopy (NIRS) time series with detection limit, which contains two testing statistics: Mean Area Under the Curve (MAUC) and slope statistic. This package applied a penalized spline method within imputation setting. Testing is conducted by a nested permutation approach within imputation. Refer to Guo et al (2018) <doi:10.1177/0962280218786302> for further details.

1. Link to package here: https://cran.r-project.org/web/packages/NIRStat/index.html
1. Reference Manual: https://cran.r-project.org/web/packages/NIRStat/NIRStat.pdf
      
Cool functions from package:     

1. **MAUCtest**: MAUC statistics based Analysis for NIRS time series. Estimate the Mean Area Under the Curve (MAUC) statistics and conduct a nonparametric test on the MAUC difference before transfusion and after transfusion. If detection limit occurs at 15.
1. **plotNIRS**: This function visualizes the NIRS time series data and estimates the underlying smoothed trend of
the NRIS based on a nonparametric regression approach.
1. **Slopetest**: Estimate the slope statistics and conduct a nonparametric based test on the slope difference before transfuion and after trasfusion. If detection limit occurs at 15


# fMRi, MRI, & qMRI

## [Package ‘brainGraph’](https://cran.r-project.org/web/packages/brainGraph/brainGraph.pdf)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: A set of tools for performing graph theory analysis of brain MRI
data. It works with data from a Freesurfer analysis (cortical thickness,
volumes, local gyrification index, surface area), diffusion tensor
tractography data (e.g., from FSL) and resting-state fMRI data (e.g., from
DPABI). It contains a graphical user interface for graph visualization and
data exploration, along with several functions for generating useful
figures.
1. Link to documentation: https://cran.r-project.org/web/packages/brainGraph/brainGraph.pdf
1. Link to repo: https://github.com/cwatson/brainGraph
1. Link to User Guide: https://cwatson.github.io/files/brainGraph_UserGuide.pdf

## [freesurferformats: R Package For Reading and Writing Neuroimaging File Formats](https://github.com/dfsp-spirit/freesurferformats)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: The 'freesurferformats' package is an R library for reading and writing neuroimaging file formats. The focus is on structural MRI file formats from the FreeSurfer brain imaging software suite, but a range of other file formats are supported as well. The package can be used to read 3D and 4D volume files (brain models, segemntations, voxel-wise results), 2D surface-based morphometry data (e.g., cortical thickness maps), brain surface meshes, atlas-based parcellations and labels, surface patches, and spatial transformation matrices in various file formats. The vast majority of formats can also be written. The related 'fsbrain' package can be used to visualize neuroimaging data directly in R.

1. Link to package summary: https://www.nitrc.org/projects/fsformats/
1. Link to repo: https://github.com/dfsp-spirit/freesurferformats



## [Methods for Quantitative Magnetic Resonance Imaging ('qMRI')](https://cloud.r-project.org/web/packages/qMRI/index.html)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: Implementation of methods for estimation of quantitative maps from Multi-Parameter Mapping (MPM) acquisitions (Weiskopf et al. (2013) ) including adaptive smoothing methods in the framework of the ESTATICS model (Estimating the apparent transverse relaxation time (R2*) from images with different contrasts, Weiskopf et al. (2014) ). The smoothing method is described in Mohammadi et al. (2017). . Usage of the package is also described in Polzehl and Tabelow (2019), Magnetic Resonance Brain Imaging, Chapter 6, Springer, Use R! Series.
1. Link to package: https://cloud.r-project.org/web/packages/qMRI/index.html
1. Link to manual: https://cloud.r-project.org/web/packages/qMRI/qMRI.pdf


## [Visualization of MRI data in R](https://www.alexejgossmann.com/MRI_viz/)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: In this blog post I present some functions which I was able to find for MRI visualization in R, and which I found to be very useful. All functions presented below presuppose an image in the NIfTI data format as input, and are very user-friendly.
         
Uses the ***oro.nifti*** package
1. Link to blog here: https://www.alexejgossmann.com/MRI_viz/
1. Same blog difference place: https://www.r-bloggers.com/2017/01/visualization-of-mri-data-in-r/

## [fsbrain: an R package for the visualization of structural neuroimaging data](https://www.biorxiv.org/content/10.1101/2020.09.18.302935v1.full.pdf)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: We introduce fsbrain, an R package for the visualization of neuroimaging data. The package can be used to visualize vertex-wise and region-wise morphometry data, parcellations, labels and
statistical results on brain surfaces in three dimensions (3D). Voxel data can be displayed in lightbox
mode. The fsbrain package offers various customization options and produces publication quality plots
which can be displayed interactively, saved as bitmap images, or integrated into R notebooks.

1. Link to preprint: https://www.biorxiv.org/content/10.1101/2020.09.18.302935v1.full.pdf
1. Link to repo: https://github.com/dfsp-spirit/fsbrain

## [Working with fMRI data using R](https://jokedurnez.github.io/validating-fmri/01-introduction/index.html)
**What is this?**
*Added Sunday Dec 13th, 2020*      
Description from site: Reading and visualising fMRI data with R/neuroconductor.

1. Link to site: https://jokedurnez.github.io/validating-fmri/01-introduction/index.html

 

## [fmri Package](https://cran.r-project.org/web/packages/fmri/fmri.pdf)
**What is this?**
*Added Sunday Dec 13th, 2020*      
Description from site: Contains R-functions to perform an fMRI analysis as described in           
Polzehl and Tabelow (2019) <DOI:10.1007/978-3-030-29184-6>,      
Tabelow et al. (2006) <DOI:10.1016/j.neuroimage.2006.06.029>,     
Polzehl et al. (2010) <DOI:10.1016/j.neuroimage.2010.04.241>,     
Tabelow and Polzehl (2011) <DOI:10.18637/jss.v044.i11>.     
           
Cool functions from package:

1. **read.NIFTI()**: Read fMRI data from NIFTI file(s)
1. **setmask()**: Add or replace mask in an fmridata object
1. **oro2fmri()**/**fmri2oro()**: Convert Between fmridata and oro.nifti
1. **cutroi()**: This functions cuts a region-of-interest (ROI) from input data
1. **fmri.cluster()**: Cluster thresholding
1. **fmri.design ()**: Return a design matrix for a linear model with given stimuli and possible polynomial drift terms
1. **fmri.designG()**: This function returns a design matrix for multi-subject fMRI data to fit a Linear Mixed-effects
Model (one-stage procedure) with given stimuli, polynomial drift terms and a set of known population parameters
1. **fmri.lmePar()**: Group maps are directly estimated from the BOLD time series data of all subjects using lme from
R package nlme to fit a Linear Mixed-effects Model with temporally correlated and heteroscedastic
within-subject errors. Voxel-wise regression analysis is accelerated by optional parallel processing
using R package parallel
1. **fmri.metaPar()**: Linear Mixed-effects Meta-Analysis model for fMRI data
1. **fmri.pvalue()**: P-values
1. **plot.fmripvalue()**: Visualize fMRI p-value maps

## [R for statistical analysis of fMRI data by Tara Madhyastha](https://neurohackademy.org/course/r-for-statistical-analysis-of-fmri-data/)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Tutorial give at Neurohackademy 2018 by Tara Madhyastha

1. Link to site in NeuroHackademy: https://neurohackademy.org/course/r-for-statistical-analysis-of-fmri-data/
1. Link to youtube video: https://youtu.be/sdbkWvFhTZ0


## [Processing fMRI Data in R by John Muschelli](https://johnmuschelli.com/Neuroimaging_in_R/fmri_proc.html#1)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Slides created by John Muschelli for processing fMRI Data in R.

1. Link to slides here: https://johnmuschelli.com/Neuroimaging_in_R/fmri_proc.html#1
1. Link to repo here: https://github.com/muschellij2/Neuroimaging_in_R


# EEG

## [Package EEGSpectralAnalysis details](https://neuroconductor.org/help/EEGSpectralAnalysis/)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: Compute and plot various spectral EEG analyses.
1. Link to documentation here: https://neuroconductor.org/help/EEGSpectralAnalysis/

## [Package eegUtils](https://neuroconductor.org/help/eegUtils/)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: A collection of functions for EEG processing. Includes import functions for Biosemi (BDF) and Neuroscan (CNT), topographical plotting, referencing, and epoching. eegUtils is a package for the processing, manipulation, and plotting of EEG data. It includes functions for importing data from a variety of file formats (including Biosemi, Brain Vision Analyzer, and EEGLAB), many of the typical steps in pre-preprocessing (filtering, referencing, artefact rejection), more advanced processing techniques (time-frequency analysis, ICA), and many types of plot that are common in the field (ERP plots, time-frequency plots, topographical scalp maps). Although it uses custom object classes, it is designed such that these are always translatable to standard R data.frames, and thus can be used with any of the myriad packages and methods that support standard R formats.

1. Link to documentation here: https://neuroconductor.org/help/eegUtils/
1. Link to repo here: https://github.com/craddm/eegUtils/


# All Neuro

## [neuropointillist](http://ibic.github.io/neuropointillist/)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: Flexible modeling of neuroimaging data in R, point by point

1. Link to site: http://ibic.github.io/neuropointillist/
1. Content:
- [Simple fMRI example](http://ibic.github.io/neuropointillist/fmri.example.html)
- [Advanced fMRI example](http://ibic.github.io/neuropointillist/fingerfootlips.example.html)
- [Permutation testing fMRI example](http://ibic.github.io/neuropointillist/fingerfootlips_permute.html)
- [Flournoy example (longitudinal)](http://ibic.github.io/neuropointillist/flournoy.example.html)
- [Correcting for multiple comparisons](http://ibic.github.io/neuropointillist/clustercorrection.html)

## [Plotting brain atlases in ggplot](https://lcbc-uio.github.io/ggseg/articles/ggseg.html)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: Plotting regions from different brain atlases ggplot2 is a handy way of displaying results or grouping of aparc data.

The function ggseg(), is based in the ggplot2 format, it is recommended to get familiarized with plotting data with ggplot2.

Out-of-the-box, ggseg() works without supplying any extra information. It will create a base plot of the aparc brain segmentations.

1. Link to site: https://lcbc-uio.github.io/ggseg/articles/ggseg.html
1. Link to ggseg vignette: https://github.com/LCBC-UiO/ggseg/blob/master/vignettes/ggseg.Rmd
1. Link to ggseg repo: https://github.com/LCBC-UiO/ggseg

## [ggsegExtra](https://github.com/LCBC-UiO/ggsegExtra)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: This package mainly contains a plotting function ggseg and data.frames of different brain atlases for plotting. Plotting results of analyses on regions or networks often involves swapping between statistical tools, like R, and software for brain imaging to correctly visualize analysis results.

This package aims to make it possible to plot results directly through R.

1. Link to documentation here: https://neuroconductor.org/help/ggseg/
1. Link to wiki here: https://github.com/LCBC-UiO/ggsegExtra/wiki/Contributing%3A-polygon-atlases-new
1. Link to repo here: https://github.com/LCBC-UiO/ggsegExtra 

## [Neuroconductor](https://neuroconductor.org/)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Description from site: Neuroconductor is an open-source platform for rapid testing and dissemination of reproducible computational imaging software. The goals of the project are to:

provide a centralized repository of R software dedicated to image analysis;
disseminate quickly software updates;
educate a large, diverse community of scientists using detailed tutorials and short courses;
ensure quality via automatic and manual quality controls; and
promote reproducibility of image data analysis.
Based on the programming language R, Neuroconductor started with 51 inter-operable packages that cover multiple areas of imaging including visualization, data processing and storage, and statistical inference. Neuroconductor accepts new R package submissions, which are subject to a formal review and continuous automated testing.

1. Link to site here: https://neuroconductor.org/

## [Neuroimaging Analysis within R](https://johnmuschelli.com/imaging_in_r/)
*Added Sunday Dec 13th, 2020*      
**What is this?**
Series of slides with code for course on Neuroimaging Analysis:
All the PDF slides are located in a zip file here.

- Introduction and R	[Slides](https://johnmuschelli.com/imaging_in_r/intro/index.html),	[PDF Slides](https://johnmuschelli.com/imaging_in_r/intro/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/intro/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/intro/index.Rmd)
- General R (not covered at ENAR)	[Slides](https://johnmuschelli.com/imaging_in_r/general_r/index.html),	[PDF Slides](https://johnmuschelli.com/imaging_in_r/general_r/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/general_r/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/general_r/index.Rmd)
- Imaging Packages in R	[Slides](https://johnmuschelli.com/imaging_in_r/imaging_r_packages/index.html)	[PDF Slides](https://johnmuschelli.com/imaging_in_r/imaging_r_packages/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/imaging_r_packages/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/imaging_r_packages/index.Rmd)
- Visualization of Images	[Slides](https://johnmuschelli.com/imaging_in_r/visualization/index.html)	[PDF Slides](https://johnmuschelli.com/imaging_in_r/visualization/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/visualization/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/visualization/index.Rmd)
- Inhomogeneity Correction	[Slides](https://johnmuschelli.com/imaging_in_r/inhomogeneity_correction_ms/index.html),	[PDF Slides](https://johnmuschelli.com/imaging_in_r/inhomogeneity_correction_ms/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/inhomogeneity_correction_ms/index.R)	[Source](https://johnmuschelli.com/imaging_in_r/inhomogeneity_correction_ms/index.Rmd)
- Brain Extraction/Segmentation	[Slides](https://johnmuschelli.com/imaging_in_r/brain_extraction_malf/index.html),	[PDF Slides](https://johnmuschelli.com/imaging_in_r/brain_extraction_malf/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/brain_extraction_malf/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/brain_extraction_malf/index.Rmd)
- Image Registration	[Slides](https://johnmuschelli.com/imaging_in_r/coregistration/index.html)	[PDF Slides](https://johnmuschelli.com/imaging_in_r/coregistration/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/coregistration/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/coregistration/index.Rmd)
- Tissue-Class Segmentation	[Slides](https://johnmuschelli.com/imaging_in_r/segmentation/index.html)	[PDF Slides](https://johnmuschelli.com/imaging_in_r/segmentation/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/segmentation/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/segmentation/index.Rmd)
- Intensity Normalization	[Slides](https://johnmuschelli.com/imaging_in_r/intensity_normalization/index.html),	[PDF Slides](https://johnmuschelli.com/imaging_in_r/intensity_normalization/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/intensity_normalization/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/intensity_normalization/index.Rmd)
- Segmentation of MS Lesions	[Slides](https://johnmuschelli.com/imaging_in_r/ms_lesion_segmentation/index.html),	[PDF Slides](https://johnmuschelli.com/imaging_in_r/ms_lesion_segmentation/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/ms_lesion_segmentation/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/ms_lesion_segmentation/index.Rmd)
- Image Harmonization	[Slides](https://johnmuschelli.com/imaging_in_r/image_harmonization/index.html)	[PDF Slides](https://johnmuschelli.com/imaging_in_r/ms_lesion_segmentation/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/image_harmonization/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/image_harmonization/index.Rmd)
- Starting with Raw (DICOM) Data (not covered)	[Slides](https://johnmuschelli.com/imaging_in_r/starting_with_raw_data/index.html),	[PDF Slides](https://johnmuschelli.com/imaging_in_r/starting_with_raw_data/index.pdf),	[R Code](https://johnmuschelli.com/imaging_in_r/starting_with_raw_data/index.R),	[Source](https://johnmuschelli.com/imaging_in_r/starting_with_raw_data/index.Rmd)

1. Link to site here: https://johnmuschelli.com/imaging_in_r/

