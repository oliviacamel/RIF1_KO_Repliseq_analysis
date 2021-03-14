# RIF1_KO_Repliseq_analysis
This directory contains the code for processing high resolution repliseq data from RPM bedgraphs. The input takes bedgraph files of S phase fractions S1 to S16. The output is a Gaussian smoothed, column-sum normalised data array that are sorted row-wise from S1 to S16 and column-wise by bins. This data array is the basis of further calculation such as Twidth, delta RT etc.
