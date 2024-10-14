# MLPaperReplication
A paper replication repository from my own work
For the First ipynb file, it is based on the 
Machine Assisted Experimentation of Extrusion-Based Bioprinting Systems

Tian S, Stevens R, McInnes BT, Lewinski NA. Machine Assisted Experimentation of Extrusion-Based Bioprinting Systems. Micromachines. 2021; 12(7):780. https://doi.org/10.3390/mi12070780
https://www.mdpi.com/1172562

I put my understanding about this paper in the first few pages, then the following steps:
### handling null instances for bioink temperature as described
### Removal of features that are more than 50% null or zero
### Imputation of missing data using KNN as described
### Encoding of categorical data (simple one-hot or BERT)
And pretrain the following model: Random Forest classification, Linear Regression, Logitsic Regression classifier, support vector classsificaiton, 
