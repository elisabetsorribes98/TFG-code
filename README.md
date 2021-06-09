# TFG-code
Bachelor's thesis code based on the assessment of Alzheimer’s Disease by using radiomics in TgF344-AD rats.

Alzheimer’s disease (AD) is a complex neurodegenerative disease that leads to progressivecognitive decline and memory loss.  Nowadays, it is still very challenging 
to diagnoseAlzheimer’s disease due to its complexity, the inter-individual differences and the latesymptoms appearance. However, the use of animal models can 
contribute to improveearly AD diagnosis in patients. Concretely, the combination of MRI images of TgF344-AD rats and radiomics could have a great potential in 
detecting quantitative imaging biomarkers of AD.

The main objectives of this project was to evaluate the ability of radiomics to discriminate between control (CTR) and transgenic animals (Tg) and also to evaluate the disease progression considering the stages young-CTR, old-CTR, young-Tg, old-Tg in three different regions, which were hippocampus, amygdala and thalamus. 

To accomplish this goal, radiomics and machine learning pipelines were developed in a Python implementation. The database was composed by 34 wildtype rats and 30 TgF344-AD animals, each of them evaluated at different ages between 3 and 18 months, resulting in 98 control images and 96 in Tg. Radiomics was applied to this database in order to obtain the corresponding texture, shape and intensity features for each region. Then, several machine learning algorithms were used to test the biomarker combination obtained from the feature selection with the aim of finding the best model that optimizes the accuracy of the classification, and therefore, to obtain highly accurate non-invasive biomarkers of the disease. 

In the binary classification of rat images between control and Tg animals, the highest accuracy reached in our method was 78.84\% using hippocampus. Regarding the classification in the aforementioned 4 groups, an accuracy value of 76.92\% was obtained in the hippocampus too. 

Radiomics showed promising results when applied in transgenic TgF334-AD rats. Both CTR and Tg as well as the different stages Young-CTR, Old-CTR, Young-Tg and Old-Tg were properly identified in hippocampus. However, age was considered as indicator of disease stage and a more accurate individual assessment could result in better classification.
