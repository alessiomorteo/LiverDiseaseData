# LiverDiseaseData
## Overview
* This repo demonstrates some simple Data Analysis and Data Science, applied in the general topic area of "Medical Analytics". 
* The work within has been done using an open source dataset that details the blood test results of anonymised individuals. The fields present represent varying tests that were undertaken for medical investigation of potential liver disease in patients. 
* None of the insights or points of discussions should be acted upon or taken as fact, all findings are purely analytical and for learning purposes


The first 5 variables are all blood tests which are thought to be sensitive to liver disorders that might arise from excessive alcohol consumption. Each line in the dataset constitutes the record of a single male individual.

Important note: The 7th field (selector) has been widely misinterpreted in the past as a dependent variable representing presence or absence of a liver disorder. This is incorrect [1]. The 7th field was created by BUPA researchers as a train/test selector. It is not suitable as a dependent variable for classification. The dataset does not contain any variable representing presence or absence of a liver disorder. Researchers who wish to use this dataset as a classification benchmark should follow the method used in experiments by the donor (Forsyth & Rada, 1986, Machine learning: applications in expert systems and information retrieval) and others (e.g. Turney, 1995, Cost-sensitive classification: Empirical evaluation of a hybrid genetic decision tree induction algorithm), who used the 6th field (drinks), after dichotomising, as a dependent variable for classification. Because of widespread misinterpretation in the past, researchers should take care to state their method clearly

## Data Source
Data available for download from https://archive.ics.uci.edu/ml/datasets/Liver+Disorders
