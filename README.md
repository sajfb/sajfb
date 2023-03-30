<!-- badges: start -->
[![CRAN stats](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-pkg.org/maint/sadjad.fakouri-baygi@mssm.edu)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://github.com/idslme/IDSL.MLP)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sadjad-fakouri-baygi-31b5a856)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=WzBF1YMAAAAJ)
<!-- badges: end -->

I am a computational software developer in the fields of natural product discovery and metabolomics specializing in mass spectrometry data sciences. I have developed several computational pipelines to process mass spectrometry data for various research applications including proteomics, metabolomics, lipidomics, exposomics, and environmental studies. My approach to computational software development is to create software packages that offer maximum automation levels, the highest precision, versatility to use in various analytical platforms, and simplicity for users to minimize laboratorial efforts. I am interested in pursuing professional positions that incorporate quantum computations in mass spectrometry data processing pipelines to improve the precision of bioactive compound discovery, or any other similar positions that align with my career goals.

## Active projects: Neural Network Models for Computational Biology

***Natural Product Discovery***
  - Developing neural network models to detect bioactive compounds in the selected fungus specimens.

***Multiomics***
  - Incorporating the computational software packages that I developed for mass spectrometry data processing with genomics and transcriptomic workflows to create robust multiomics pipelines in the context of Alzheimer diseases and chemical exposures using neural network models.

## Completed projects: Mass Spectrometry Data Processing Workflows

<p align="center">
  <a href="https://metabolomicscentre.ca/metabonews-november-issue-mana-conference-presenters/">
    <img src="https://github.com/sajfb/sajfb/blob/main/integrated.png" alt="image description" width="700">
  </a>
</p>

  - [IDSL.ICA](https://github.com/idslme/IDSL.ICA) (Integrated Compound Annotation) is a full-scale annotation workflow to facilitate integration of metabolomics data for multi-omics analyses. (pending release ... )

  - [IDSL.IPA](https://github.com/idslme/IDSL.IPA) (Intrinsic Peak Analysis) is a chromatographic peak-picking software package which is able to screen at lowest signal intensities (S/N > 2). IDSL.IPA is able to pair isotopologues with a fixed distance (e.g. &Delta;C = <sup>13</sup>C - <sup>12</sup>C = 1.003354835336 Da), to detect non-ideal chromatographic peaks, to correct retention time drifts using endogenous index markers, to align peaks (m/z-RT pairs) across population size studies (N > 200), to fill gaps on the aligned peak tables, to annotate peaks, and to visualize extracted ion chromatograms (EICs) and total ion chromatograms (TICs).

  - [IDSL.FSA](https://github.com/idslme/IDSL.FSA) (Fragmentation Spectra Analysis) is a computational fragmentation annotation workflow to annotate *.msp* (mass spectra format) and *.mgf* (Mascot generic format) fragmentation data files rapidly via measurement of spectral entropy and/or cosine similarity even when precursor values are not available nor reliable. IDSL.FSA also may be employed to process bottom-up proteomics data.

  - [IDSL.CSA](https://github.com/idslme/IDSL.CSA) (Composite Spectra Analysis) is a pipeline to deconvolute fragmentation spectra from Data Dependent Acquisition (DDA), and various Data-Independent Acquisition (DIA) methods such as MS<sup>E</sup>, and All-Ion Fragmentation (AIF) analyses.

  - [IDSL.UFA](https://github.com/idslme/IDSL.UFA) (United Formula Annotation) is a computationally enhanced pipeline to annotate chromatographic peaks with molecular formula using an isotopic profile matching approach. IDSL.UFA only requires MS1 level data which is especially beneficial when MS/MS data are not available. The IDSL.UFA pipeline can screen for isotopic profiles of up to 10<sup>8</sup> molecular formulas using a computationally efficient algorithm without any memory complications.

  - [IDSL.UFAx](https://github.com/idslme/IDSL.UFAx) (exhaustive UFA) was developed to annotate chromatographic peaks using an exhaustive chemical enumeration-based approach. This package can perform elemental composition calculations using the following 15 elements: C, B, Br, Cl, K, S, Si, N, H, As, F, I, Na, O, and P. IDSL.UFAx is also able to screen for isotopic profiles of 10<sup>27</sup> molecular formulas without any memory complications; however, IDSL.UFAx is not computationally as fast as IDSL.UFA.

  - [IDSL.SUFA](https://github.com/idslme/IDSL.SUFA) is a simplified version of the IDSL.UFA package to calculate isotopic profiles and adduct formulas from molecular formulas with no dependency on other R packages for online tools such as [isotopic profile calculator](https://ipc.idsl.me/). The IDSL.SUFA package also provides functions to process user-defined adduct formulas.

  - [IDSL.NPA](https://github.com/idslme/IDSL.NPA) (Nominal Peak Analysis) is a pipeline for processing nominal mass spectrometry data to create and annotate .msp files for untargeted MS/MS workflows.

  - [IDSL.MXP](https://github.com/idslme/IDSL.MXP) (Mass Spectrometry Parser) is a light and fast parser for mzML/mzXML/netCDF mass spectrometry data files. IDSL.MXP is especially a proven tool to read corrupted mass spectrometry files.

  - An [IPDC](https://github.com/sajfb/Isotopic-Profile-Deconvolution-Chromatogram-IPDC-algorithm) (Isotopic Profile Deconvoluted Chromatogram) algorithm to screen biologically complex environmental matrices for unknown contaminants. The IPDC algorithm was successfully employed in five different projects during my PhD.
