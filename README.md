# TFG-code
Bachelor's thesis code based on the assessment of Alzheimer’s Disease by using radiomics in TgF344-AD rats.

Alzheimer’s disease (AD) is a complex neurodegenerative disease that leads to progressivecognitive decline and memory loss.  Nowadays, it is still very challenging 
to diagnoseAlzheimer’s disease due to its complexity, the inter-individual differences and the latesymptoms appearance. However, the use of animal models can 
contribute to improveearly AD diagnosis in patients. Concretely, the combination of MRI images of TgF344-AD rats and radiomics could have a great potential in 
detecting quantitative imaging biomarkers of AD.

The main objectives of this project is to evaluate the ability of radiomics to discriminatebetween control (CTR) and transgenic animals (Tg) and also to evaluate 
the disease pro-gression considering the groups young-CTR, old-CTR, young-Tg, old-Tg in three differentregions, which are hippocampus, amygdala and thalamus. 

To accomplish this goal, radiomics and machine learning pipelines are developed in a Python implementation. The database is composed by 34 wildtype rats and 30 
TgF344-AD animals, each of them evaluated at different ages between 3 and 18 months, resulting in98 control images and 96 in Tg. Radiomics is applied to this 
database in order to obtainthe corresponding texture, shape and intensity features for each region. Then, severalmachine learning algorithms are used to test 
the biomarker combination obtained fromthe feature selection with the aim of finding the best model that optimizes the accuracyof the classification, and 
therefore, to obtain highly accurate non-invasive biomarkers ofthe disease.In the binary classification of rat images between control and Tg animals, the 
highest accuracy reached in our method is 80.76% using hippocampus. Regarding the classification in the aforementioned 4 groups, an accuracy value of 82.69% 
is obtained in thehippocampus too. 
