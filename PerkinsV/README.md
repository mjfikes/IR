# IR
Institutional Research repository

## Perkins V Performance Measure Tool

This utility is for calculating Perkins Performance measures 1P1, 2P1, and 3P1 by CIP, in addition to Special Population measures
This is also available in a Google Colab notebook: https://githubtocolab.com/mjfikes/IR/blob/main/PerkinsV/PerkinsV.ipynb

### Usage

This utility was designed to be run on the CTEA-1 and not CTEA-2. The program assumes
CTEA-1A and CTEA-1B have already been combined into one file. The code looks for CTEA.xlsx
but will prompt for a different file if it is not found.

If you do not have your files combined, you may first use the CTEA_Merge notebook to combine your files.
It requires that they are named CTEA_1A.xlsx and CTEA_1B.xlsx to run, but will join your data and return a CTEA.xlsx for use with the performance measure tool.

The utility assumes the data is numeric and not descriptive text. 
The code can be altered to compensate for different responses in the data.

The non-traditional crosswalk will be downloaded and joined to the CTEA data automatically for calculating measure 3P1.
Combined results will be displayed, and a summary file for each CIP with all 3 measures can be either viewed or exported to Excel when complete.


