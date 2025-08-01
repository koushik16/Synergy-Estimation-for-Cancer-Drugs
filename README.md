# Cancer Drug Synergy Prediction using GNN and GCNN

---------------------------------


### Project Objective

Implementing deep learning techniques to compute synergy scores between two drugs for Cancer Treatment. We need to compute a viable score for a combination of drug effects on cancer cells.

Our models use the chemical structure of drugs and genomic information of various cancer cell lines as input information, a normalization strategy to justify the input data heterogeneity, and tapered layers to model drug synergies.



### Data Source


### Technical Details about Neural Networks

Activation functions used:

1. TanH (Tangential Hyperbolic)
2. ReLu (Rectified Linear)




### Model Description:
![img.png](img.png)



# DeepSynergy

While drug combination therapies are a well-established concept in cancer treatment, identifying novel synergistic combinations is challenging due to the size of combinatorial space. However, computational approaches have emerged as a time- and cost-efficient way to prioritize combinations to test, based on recently available large-scale combination screening data. Recently, Deep Learning has had an impact in many research areas by achieving new state-of-the-art model performance. However, Deep Learning has not yet been applied to drug synergy prediction, which is the approach we present here, termed DeepSynergy. DeepSynergy uses chemical and genomic information as input information, a normalisation strategy to account for input data heterogeneity, and conical layers for modelling. DeepSynergy significantly outperformed other machine learning methods like Gradient Boosted Trees, Random Forests, Support Vector Machines, and Elastic Nets on this large publicly available synergy data set based on the MSE, which is an improvement by 7.2% over the second best method. The mean Pearson correlation coefficient between the measured and the predicted values of DeepSynergy is 0.73. Applying DeepSynergy for classification resulted in an AUC of 0.90. 

# Code
Example code for data normalization and a cross validation run is provided. 

# Data
Data for the example code as well as all labels and SMILES for the compounds are provided on:<br> 
http://www.bioinf.jku.at/software/DeepSynergy/

# Webservice
The predictions of DeepSynergy are provided via a webservice:<br>
http://shiny.bioinf.jku.at/DeepSynergy/

