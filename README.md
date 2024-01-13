<!-- badges: start -->
[![CRAN stats](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://CRAN.R-project.org/package=IDSL.IPA)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://github.com/idslme/IDSL_MINT)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://github.com/idslme/IDSL_MINT)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sadjad-fakouri-baygi-31b5a856)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=WzBF1YMAAAAJ)
<!-- badges: end -->

I'm a data scientist with expertise in cheminformatics and metabolomics focusing on small molecule discovery and mass spectrometry data sciences (see my [award news](https://mountsinaiexposomics.org/dr-sadjad-fakouri-baygi-wins-the-mark-p-styczynski-early-career-award-in-computational-metabolomics-from-metabolomics-association-of-north-america-mana/) from Metabolomics Association of North America (MANA) and my presentation details [here](https://metabolomicscentre.ca/metabonews-november-issue-mana-conference-presenters)).

I've crafted multiple computational pipelines designed for untargeted mass spectrometry data processing across diverse research domains including metabolomics, lipidomics, exposomics, and environmental studies. My research philosophy emphasizes on maximal automation, highest precision, multi-platform compatibility, and user-friendly interfaces to minimize lab-based experiments.

I'm actively exploring opportunities that integrate deep learning into cheminformatics and bioinformatics workflows enhancing the accuracy of compound identification. I'm open to roles that resonate with this vision and align with my broader professional aspirations.


## Completed projects
#### Mass Spectrometry Data Processing Workflows at the [Integrated Data Science Laboratory for Metabolomics and Exposomics](https://github.com/idslme)

  - [IDSL_MINT](https://github.com/idslme/IDSL_MINT) (Mass INTerpretator) is deep learning framework to further interpret unannoated mass spectrometry data using deep cheminformatics analyses.
    
    

#### Full-sacle metabolomics annotation pipeline
<p align="center">
  <img src="https://github.com/sajfb/sajfb/blob/main/integrated.png" alt="image description" width="500">
</p>

  - [IDSL.ICA](https://github.com/idslme/IDSL.ICA) (Integrated Compound Annotation) is a full-scale annotation workflow to facilitate integration of metabolomics data for multi-omics analyses. (pending release ... )

  - [IDSL.IPA](https://github.com/idslme/IDSL.IPA) (Intrinsic Peak Analysis) is a chromatographic peak-picking software package which is able to screen at lowest signal intensities (S/N > 2). IDSL.IPA is able to pair isotopologues with a fixed distance (e.g. &Delta;C = <sup>13</sup>C - <sup>12</sup>C = 1.003354835336 Da), to detect non-ideal chromatographic peaks, to correct retention time drifts using endogenous index markers, to align peaks (m/z-RT pairs) across population size studies (N > 200), to fill gaps on the aligned peak tables, to annotate peaks, and to visualize extracted ion chromatograms (EICs) and total ion chromatograms (TICs).

  - [IDSL.FSA](https://github.com/idslme/IDSL.FSA) (Fragmentation Spectra Analysis) is a computational fragmentation annotation workflow to annotate *.msp* (mass spectra format) and *.mgf* (Mascot generic format) fragmentation data files rapidly via measurement of spectral entropy and/or cosine similarity even when precursor values are not available nor reliable. IDSL.FSA also may be employed to process bottom-up proteomics data.

  - [IDSL.CSA](https://github.com/idslme/IDSL.CSA) (Composite Spectra Analysis) is a pipeline to deconvolute fragmentation spectra from Data Dependent Acquisition (DDA), and various Data-Independent Acquisition (DIA) methods such as SWATH-MS, MS<sup>E</sup>, and All-Ion Fragmentation (AIF) analyses.

  - [IDSL.UFA](https://github.com/idslme/IDSL.UFA) (United Formula Annotation) is a computationally enhanced pipeline to annotate chromatographic peaks with molecular formula using an isotopic profile matching approach. IDSL.UFA only requires MS1 level data which is especially beneficial when MS/MS data are not available. The IDSL.UFA pipeline can screen for isotopic profiles of up to 10<sup>8</sup> molecular formulas using a computationally efficient algorithm without any memory complications.

  - [IDSL.UFAx](https://github.com/idslme/IDSL.UFAx) (exhaustive UFA) was developed to annotate chromatographic peaks using an exhaustive chemical enumeration-based approach. This package can perform elemental composition calculations using the following 15 elements: C, B, Br, Cl, K, S, Si, N, H, As, F, I, Na, O, and P. IDSL.UFAx is also able to screen for isotopic profiles of 10<sup>27</sup> molecular formulas without any memory complications; however, IDSL.UFAx is not computationally as fast as IDSL.UFA.

  - [IDSL.SUFA](https://github.com/idslme/IDSL.SUFA) is a simplified version of the IDSL.UFA package to calculate isotopic profiles and adduct formulas from molecular formulas with no dependency on other R packages for online tools such as [isotopic profile calculator](https://ipc.idsl.me/). The IDSL.SUFA package also provides functions to process user-defined adduct formulas.

  - [IDSL.NPA](https://github.com/idslme/IDSL.NPA) (Nominal Peak Analysis) is a pipeline for processing nominal mass spectrometry data to create and annotate .msp files for untargeted MS/MS workflows.

  - [IDSL.MXP](https://github.com/idslme/IDSL.MXP) (Mass Spectrometry Parser) is a light and fast parser for mzML/mzXML/netCDF mass spectrometry data files. IDSL.MXP is especially a proven tool to read corrupted mass spectrometry files.

#### Computational mass spectrometry pipelines for environmental chemometrics projects as part of my doctoral research
  - An [IPDC](https://github.com/sajfb/Isotopic-Profile-Deconvolution-Chromatogram-IPDC-algorithm) (Isotopic Profile Deconvoluted Chromatogram) algorithm to screen biologically complex environmental matrices for unknown contaminants. The IPDC algorithm was successfully employed in five different projects during my PhD.
