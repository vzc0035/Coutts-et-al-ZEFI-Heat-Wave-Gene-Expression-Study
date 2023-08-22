# Coutts-et-al-ZEFI-Heat-Wave-Gene-Expression-Study

In this study, sample data was collected in triplicate. We first screened the data by removing replicates more than 0.5 Cq from the mean. When multiple replicates were more than 0.5 Cq from the mean, the replicate more than 1 standard deviation from the mean was removed and a new mean was calculated. If a replicate was still more than 0.5 Cq from the mean, the entire sample was removed from analysis.

File explanation:

admin_* files are raw data files gathered from the BioRad CFX software.

TCZefiHeat_Field/Lab_Gene.csv files were used to test assumptions.

FinalTCZefiHeatField/LabNormTransData.csv uses the same data, but displayed in a way that allows for easier data analysis and combines all the genes together.

TCZefiHeatqPCRPipeline.Rmd is the pipeline from R Studio that was used to analyze the data, with TCZefiHeatqPCRPipeline.nb.html as the HTML version of this document.
