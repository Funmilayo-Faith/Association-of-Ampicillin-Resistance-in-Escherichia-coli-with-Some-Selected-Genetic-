# Association-of-Ampicillin-Resistance-in-Escherichia-coli-with-Some-Selected-Genetic-Markers

## Description
The project analyzed the relationship between ampicillin resistance in the above named organism and biomarkers such as marR and soxS.

### Materials used 
Dataset obtained from EMBL-EBI portal, Microsoft Excel, GraphPad Fischer test calculator.

### Tools Used
1. Chi-square test
2. Fisher test
3. Odd Ratio


### Method
From the EMBL-EBI portal, dataset containing combined phenotype and genotype was download. This dataset was filtered for Escherichia coli and Ampicillin. In Power query editor on Microsoft Excel, the dataset was filtered for CLSI (for ensuring uniformity in antimicrobial susceptibility testing method), two forms of resistance phenotype (preventing ambiguity when analyzing the data). A total of 750 unique columns remained and was loaded for analysis.


### Discussion
4 genes were seen as related to resistance phenotype in tis organism for ampicillin. They are marR, soxS, soxR and acrR_1. Of these, only marR and soxS were selected as both had both resistant and susceptible phenotypes.

### Conclusion
marR and soxS genes are regulators involved in multidrug resistance in E. coli. marR gene codes for the repressor that regulates the activity of the efflux pump of the bacterium.  This explains why the presence of this gene accounts for susceptibility as it ensures the normal activity of the bacterium’s efflux pump when not in danger. 


### Limitation
The number of isolates with soxS gene was very small compared to those with marR gene. This limits generalization of these findings. Also, the presence of a gene does not necessarily mean it will be expressed. 
