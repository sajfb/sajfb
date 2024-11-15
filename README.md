<!-- badges: start -->
[![CRAN stats](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://CRAN.R-project.org/package=IDSL.IPA)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://github.com/idslme/IDSL_MINT)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://github.com/idslme/IDSL_MINT)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sadjad-fakouri-baygi-31b5a856)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=WzBF1YMAAAAJ)
<!-- badges: end -->

I'm an award-winning data scientist bridging cheminformatics and metabolomics focusing on small molecule discovery and mass spectrometry data sciences (see my [award news](https://mountsinaiexposomics.org/dr-sadjad-fakouri-baygi-wins-the-mark-p-styczynski-early-career-award-in-computational-metabolomics-from-metabolomics-association-of-north-america-mana/) from Metabolomics Association of North America (MANA) and my presentation details [here](https://metabolomicscentre.ca/metabonews-november-issue-mana-conference-presenters)).

I've crafted multiple computational pipelines designed for untargeted mass spectrometry data processing across diverse research domains including metabolomics, lipidomics, exposomics, and environmental studies. My software development philosophy emphasizes on maximal automation, highest precision, multi-platform compatibility, and user-friendly interfaces to minimize lab-based experiments.

I am always driven to advance next-generation AI for chemistry and biological applications.

## Developing AI-Powered Digital Twins for Bioreactors at [Aropha](https://github.com/Aropha)
I am currently leading the development of digital twins for bioreactors at Aropha utilizing advanced AI models to simulate bioprocesses. By creating virtual replicas of our bioreactor systems, we aim to predict performance and scale up the company’s capacity effectively. This work integrates cutting-edge AI engines with bioprocess engineering.

## Completed projects
#### Mass Spectrometry Data Processing Workflows at the [Integrated Data Science Laboratory for Metabolomics and Exposomics](https://github.com/idslme)

<p align="center">
  <img src="https://github.com/sajfb/sajfb/blob/main/Comprehensive_Untargeted_Metabolomics_Workflow.PNG" alt="image description">
</p>

Tools shown in this diagram form a comprehensive pipeline for full-scale untargeted metabolomics workflow to efficiently process, and annotate large-scale mass spectrometry data. The integration of peak detection, formula annotation, fragmentation analysis, and data parsing facilitates any muti-omics or untartgeted compound discovery projects.
[IDSL_MINT](https://github.com/idslme/IDSL_MINT) (Mass INTerpretator) utilizes deep learning and cheminformatics to interpret MS/MS data. [IDSL.IPA](https://github.com/idslme/IDSL.IPA) (Intrinsic Peak Analysis) is a chromatographic peak-picking software capable of detecting low-intensity signals (S/N > 2), pairing isotopologues with a fixed distance (e.g. &Delta;C = <sup>13</sup>C - <sup>12</sup>C = 1.003354835336 Da), correcting retention time drifts, aligning peaks across large studies (N > 200), filling gaps, and visualizing extracted and total ion chromatograms. [IDSL.FSA](https://github.com/idslme/IDSL.FSA) (Fragmentation Spectra Analysis) rapidly annotates fragmentation data files (*.msp* and *.mgf*) using spectral entropy or cosine similarity, even without reliable precursor values, and can process bottom-up proteomics data. [IDSL.CSA](https://github.com/idslme/IDSL.CSA) (Composite Spectra Analysis) deconvolutes fragmentation spectra from various acquisition methods like DDA and DIA (SWATH-MS, MSE, AIF). [IDSL.UFA](https://github.com/idslme/IDSL.UFA) (United Formula Annotation) and its exhaustive version IDSL.UFAx annotate chromatographic peaks with molecular formulas using isotopic profile matching; IDSL.UFA handles up to 10<sup>8</sup> formulas efficiently, while [IDSL.UFAx](https://github.com/idslme/IDSL.UFAx) can screen 10<sup>27</sup> formulas using 15 elements, though it is less computationally fast. [IDSL.SUFA](https://github.com/idslme/IDSL.SUFA) simplifies isotopic profile and adduct formula calculations without dependencies on other R packages. [IDSL.NPA](https://github.com/idslme/IDSL.NPA) (Nominal Peak Analysis) processes nominal mass spectrometry data to create and annotate *.msp* files for untargeted MS/MS workflows. Lastly, [IDSL.MXP](https://github.com/idslme/IDSL.MXP) (Mass Spectrometry Parser) is a lightweight and fast parser for mass spectrometry data files, capable of reading corrupted mass spectrometry files.

#### Computational mass spectrometry pipelines for environmental cheminformatics projects as part of my doctoral research
  - An [IPDC](https://github.com/sajfb/Isotopic-Profile-Deconvolution-Chromatogram-IPDC-algorithm) (Isotopic Profile Deconvoluted Chromatogram) algorithm to screen biologically complex environmental matrices for unknown contaminants using chemometric methods. The IPDC algorithm was successfully employed in five different projects during my PhD.
