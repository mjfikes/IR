# IR
Institutional Research repository

## Perkins V Performance Measure Tool

This utility is for calculating Perkins Performance measures 1P1, 2P1, and 3P1 by CIP, in addition to Special Population measures
This is also available in a Google Colab notebook: https://colab.research.google.com/drive/1nT2Qt_woleoqYNBCqBn5dYWGo5EV2Cws?usp=sharing

## Usage

This utility was designed to be run on the CTEA-1 and not CTEA-2. The program assumes
CTEA-1A and CTEA-1B have already been combined into one file. The code looks for CTEA.xlsx
but will prompt for a different file if it is not found.

The utility assumes the data is numeric and not descriptive text. 
The code can be altered to compensate for different responses in the data.

The non-traditional crosswalk will be downloaded and joined to the CTEA data automatically for calculating measure 3P1.
Combined results will be displayed, and a summary file for each CIP with all 3 measures can be either viewed or exported to Excel when complete.


