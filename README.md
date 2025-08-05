# RAW_DATA_RFSoC-Based-Validation-of-a-Multi-Path-RF-Front-End-for-Wideband-Spectrum-Analysis


Repository Description
The repository contains the raw experimental data associated with the article “Design, Implementation, and RFSoC‑Based Validation of a Multi‑Path RF Front‑End for Wideband Spectrum Analysis”, intended for publication in Results in Engineering (RINENG) (https://www.sciencedirect.com/journal/results-in-engineering). The paper presents the design and characterization of a multi‑path RF front‑end that expands the analysis bandwidth of an RFSoC‑based FPGA platform from 2.5 GHz to 8 GHz.

The repository is structured as follows:

Measurements_summary.xlsx – Summarized results of all key measurements (Insertion Loss, Noise Figure, 1 dB compression points,IIP3, OIP3).

NF.xlsx – Raw PNOUT data and corresponding Insertion Loss values used to calculate the Noise Figure for three measurement sets across the five reception paths.

P1dB/ – Raw data for 1 dB compression point measurements for all five reception paths. Calculated P1dB values are also provided in P1dB.xlsx.

IIP3/ – Raw data for IIP3 (third‑order input intercept point) measurements across three sets and five reception paths. OIP3 (third‑order output intercept point) is computed using the relation OIP3 = IIP3 + Insertion Loss and reported in Measurements_summary.xlsx.

ZNB_InsLoss_GroupDelay/ – Raw insertion loss (three measurement sets) and group delay data acquired with a Rohde & Schwarz ZNB VNA over 10 MHz to 8 GHz with 10 MHz resolution, used to validate earlier generator‑analyzer‑based insertion loss measurements.

README.md – Overview of repository contents and measurement methodology.

Measurement details:

Insertion Loss: Directly measured over 10 MHz–8 GHz with 100 MHz resolution (summarized in Measurements_summary.xlsx).

Noise Figure: Computed from PNOUT and insertion loss data in NF.xlsx for three sets of measurements.

1 dB Compression Point: Raw data and processed results for all five reception paths in P1dB/.

IIP3/OIP3: Three sets of IIP3 data across five paths; OIP3 calculated using the standard relationship.

VNA Measurements: High‑resolution (10 MHz) insertion loss and group delay measurements with a Rohde & Schwarz ZNB VNA to confirm initial results and characterize phase response.

This dataset ensures transparency and reproducibility of the reported results, providing access to all raw and processed data supporting the conclusions of the study.

**Citation**
If you use this dataset in your research or publication, please cite the associated work or acknowledge the authors accordingly.
**Note:** A link to the publication will be provided here once it becomes available.
