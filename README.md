I am a data scientist with eight years experience in the field of computational mass spectrometry. I have developed a number of computational pipelines to process mass spectrometry data for various research applications such as proteomics, exposomics, metabolomics, lipidomics, and environmental studies. My research philosophy in computational pipeline development is to develop software packages which are able to offer maximum automation levels, highest precision, versatility to use in various analytical platforms, and simplicity for users to minimize laboratorial efforts. To pursue my career goals, I am interested in professional positions to incorporate machine learning algorithms in mass spectrometry data processing pipelines to further improve precision of untargeted workflows or any other similar positions.

**Active projects**

  - [IDSL.FSA](https://github.com/idslme/IDSL.FSA) (Fragmentation Spectra Analysis) is a computational fragmentation annotation workflow to annotate .msp (mass spectra format) and .mgf (Mascot generic format) fragmentation data files quickly via measurement of spectral entropy and/or cosine similarity even when precursor values are not available nor reliable. IDSL.FSA also may be employed to process bottom-up proteomics data.

  - [IDSL.CSA](https://github.com/idslme/IDSL.CSA) (Composite Spectra Analysis) was developed to deconvolute fragmentation spectra from Data Dependent Acquisition (DDA), and various Data-Independent Acquisition (DIA) methods such as MS<sup>E</sup>, and All-Ion Fragmentation (AIF) analyses.

  - [IDSL.NPA](https://github.com/idslme/IDSL.NPA) (Nominal Peak Analysis) is a pipeline for processing nominal mass spectrometry data to create and annotate .msp files for untargeted MS/MS workflows.

**Completed projects**

  - An [IPDC](https://github.com/sajfb/Isotopic-Profile-Deconvolution-Chromatogram-IPDC-algorithm) (Isotopic Profile Deconvoluted Chromatogram) algorithm to screen biologically complex environmental matrices for unknown contaminants. The IPDC algorithm was successfully employed in five different projects during my PhD.

  - [IDSL.IPA](https://github.com/idslme/IDSL.IPA) (Intrinsic Peak Analysis) is a chromatographic peak-picking software package which is able to screen at lowest signal intensities (S/N > 2). IDSL.IPA is able to pair isotopologues within a fixed distance (e.g. &Delta;C = <sup>13</sup>C - <sup>12</sup>C = 1.003354835336 Da), to detect non-ideal chromatographic peaks, to correct retention time drifts using endogenous index markers, to align peaks (m/z-RT pairs) across population size studies (N > 200), to fill gaps on the aligned peak tables, to annotate peaks, and to visualize extracted ion chromatograms (EICs) and total ion chromatograms (TICs).

  - [IDSL.UFA](https://github.com/idslme/IDSL.UFA) (United Formula Annotation) is a computationally enhanced pipeline to annotate chromatographic peaks with molecular formula using an isotopic profile matching approach. IDSL.UFA only requires MS1 level data which is especially beneficial when MS/MS data are not available. The IDSL.UFA pipeline can screen for isotopic profiles of up to 10<sup>8</sup> molecular formulas using a computationally efficient algorithm without any memory complications.

  - [IDSL.UFAx](https://github.com/idslme/IDSL.UFAx) (exhaustive UFA) was developed to annotate chromatographic peaks using an exhaustive chemical enumeration-based approach. This package can perform elemental composition calculations using the following 15 elements : C, B, Br, Cl, K, S, Se, Si, N, H, As, F, I, Na, O, and P. IDSL.UFAx is also able to screen for isotopic profiles of 10<sup>27</sup> molecular formulas without any memory complications; however, IDSL.UFAx is not computationally as fast as IDSL.UFA.

  - [IDSL.MXP](https://github.com/idslme/IDSL.MXP) (Mass Spectrometry Parser) is a light and fast parser for mzML/mzXML/netCDF mass spectrometry data files. IDSL.MXP is especially a proven tool to read corrupted mass spectrometry files.

  - [IDSL.SUFA](https://github.com/idslme/IDSL.SUFA) is a simplified version of the IDSL.UFA package to calculate isotopic profiles and adduct formulas from molecular formulas with no dependency on other R packages for online tools such as [isotopic profile calculator](https://ipc.idsl.me/). The IDSL.SUFA package also provides functions to process user-defined adduct formulas.
