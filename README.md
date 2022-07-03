I am a data scientist in the field of computational mass spectrometry. I have developed a number of computational pipelines to process mass spectrometry data for various research applications such as proteomics, exposomics, metabolomics, lipidomics, and environmental studies. My research philosophy in computational mass spectrometry is to develop software packages which are able to offer maximum automation levels, highest precision, minimum laboratorial efforts, versatility to use in various analytical platforms, and simplicity for users. To pursue my career goals, I am interested in professional positions to incorporate machine learning algorithms in mass spectrometry data processing pipelines to further improve precision of untargeted workflows or any other similar positions.

**Active projects**

  - [IDSL.FSA](https://github.com/idslme/IDSL.FSA) (Fragmentation Spectra Analyzer) is a computational fragmentation identification workflow to annotate .msp files quickly via measurement of spectral entropy similarity even when precursor values are not available nor reliable. IDSL.FSA also may be employed to query bottom-up proteomics data.

  - [IDSL.CSA](https://github.com/idslme/IDSL.CSA) (Composite Spectra Analyzer) is under development to deconvolute fragmentation spectra from Data Dependent Acquisition (DDA), and various Data-Independent Acquisition (DIA) methods such as MS<sup>E</sup>, and All-Ion Fragmentation (AIF) analyses.

  - [IDSL.NPA](https://github.com/idslme/IDSL.NPA) (Nominal Peak Analyzer) is a pipeline for processing nominal mass spectrometry data to create .msp files for untargeted MS/MS workflows.

**Completed projects**

  - An [IPDC](https://github.com/sajfb/Isotopic-Profile-Deconvolution-Chromatogram-IPDC-algorithm) (Isotopic Profile Deconvoluted Chromatogram) algorithm to screen biologically environmental complex matrices for unknown contaminants. The IPDC algorithm was employed in five different projects.

  - [IDSL.IPA](https://github.com/idslme/IDSL.IPA) (Intrinsic Peak Analyzer) is a chromatographic peak-picking software package which is able to screen at lowest signal intensities (S/N > 2). IDSL.IPA is able to pair isotopologues with a fixed distance (e.g. ∆C = <sup>13</sup>C - <sup>12</sup>C = 1.003354835336 Da), to smooth chromatographic peaks using a loess method to preserve the overall peak shapes, retention time drifts correction using indigenous index markers and peak alignment across population size studies (N > 200), gap filling, peak annotation and visualization of extracted ion chromatograms (EICs) and total ion chromatograms (TICs).

  - [IDSL.UFA](https://github.com/idslme/IDSL.UFA) (United Formula Annotation) is a computationally enhanced pipeline to annotate chromatographic peaks with molecular formula using an isotopic profile matching approach. IDSL.UFA is especially beneficial when MS/MS data is not available.

  - [IDSL.UFAx](https://github.com/idslme/IDSL.UFAx) (exhaustive UFA) was developed to annotate chromatographic peaks using an exhaustive chemical enumeration-based approach. This package can perform elemental composition calculations using the following 15 elements : C, B, Br, Cl, K, S, Se, Si, N, H, As, F, I, Na, O, and P.

  - [IDSL.MXP](https://github.com/idslme/IDSL.MXP) (Mass Spectrometry Parser) is a light and fast parser for mzML/mzXML/netCDF mass spectrometry data files.

  - [IDSL.SUFA](https://github.com/idslme/IDSL.SUFA) is a simplified version of the IDSL.UFA package to calculate isotopic profiles and adduct formulas from molecular formulas with no dependency on other R packages for online tools such as [isotopic profile calculator](https://ipc.idsl.me/). The IDSL.SUFA package also provides functions to process user-defined adduct formulas.
