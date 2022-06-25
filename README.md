I'm a computational mass spectrometry data scientist. I have developed a number of computational pipelines to process mass spectrometry data for various research applications such as computational exposomics, metabolomics, lipidomics, and environmental studies. To pursue my research in computational mass spectrometry, My research philosophy in computational mass spectrometry is to develop software packages which are able to offer a maximum level of data analysis automation, highest precision, minimizing laboratorial efforts, versatility to use in various analytical platforms, and simplicity for users. To pursue my career goals, I am interested in professional positions to incorporate machine learning algorithms in mass spectrometry data processing to further improve precision of untargeted mass spectrometry workflows or any other similar positions.

**Active projects**

IDSL.CSA (Composite Spectra Analyzer) is being developed to deconvolute fragmentation spectra from Data Dependent Acquisition (DDA) analysis, and various Data-Independent Acquisition (DIA) methods such as MS^E, and All-Ion Fragmentation (AIF). The IDSL.CSA package is also able to annotate standard .msp files using mass spectral entropy similarity.

IDSL.NPA (Nominal Peak Analyzer is a pipeline for processing nominal mass spectrometry data to create .msp files for untargeted MS/MS workflows.

**Completed projects**

An IPDC (Isotopic Profile Deconvoluted Chromatogram) algorithm: To screen biologically environmental complex matrices for unknown contaminants. The IPDC algorithm was employed in five different projects.

IDSL.IPA is a peak-picking software package which is able to screen at lowest signal intensities (S/N >= 2). IDSL.IPA is able to pair isotopologues with a fixed distance (e.g. ), to smooth chromatographic peaks using a loess method to preserve the overall peak shapes, retention time drifts correction using indigenous index markers, large-scale peak alignment (N > 2000), gap filling, peak annotation and visualization of extracted ion chromatograms (EICs) and total ion chromatograms (TICs).

IDSL.UFA is a computationally enhanced pipeline to annotate chromatographic peaks with molecular formula using an isotopic profile matching approach. IDSL.UFA is especially beneficial when MS/MS data is not available.

IDSL.UFAx was developed to annotate chromatographic peaks using an exhaustive chemical enumeration-based approach. This package can perform elemental composition calculations using the following 15 elements : C, B, Br, Cl, K, S, Se, Si, N, H, As, F, I, Na, O, and P.

IDSL.MXP is a light and fast parser for mzML/mzXML/netCDF mass spectrometry data files.

IDSL.SUFA is a simplified version of the IDSL.UFA package to calculate isotopic profiles and adduct formulas from molecular formulas with no dependency on other R packages for online tools. The IDSL.SUFA package has functions to process user-defined adduct formulas.
