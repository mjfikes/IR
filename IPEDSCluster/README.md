# IR
Institutional Research repository

## IPEDS Cohort Clustering Model

This code is set up to find similar IPEDS schools based on a given UNITID. 
The code will obtain values from IPEDS directly and filter by some of the target school characteristics. 
Some of the filters are set up to limit data to only 2-year public schools. 
These are noted with comments in the code and can be altered to find other groups.

The code is not entirely automated, the number of clusters should be modified based on the results of the generated dendrograms. 
Information on reading dendrograms is included where the first chart is generated.

This example resulted in exactly 10 schools after some filtering. 
Your results may vary and you may wish to keep a larger initial cluster and filter it manually by looking at programs offered at the different comparison institutions. 

The method was based on a white paper from Dr. Andrew J. Luna and Austin Peay State University.