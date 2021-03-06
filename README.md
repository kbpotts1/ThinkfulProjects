## ***Below are brief summaries of recent projects I've been working on:***


**Temporal Fluctuation in Fruit Resource Availability in a Tropical Forest**

- Understanding the nature of temporal variability in fruit production by tropical forest trees can inform predictions about potential impacts of climate change on the animal populations that rely on these trees as food sources. 

- I investigated these issues using data collected from a site of long-term research on both plant phenology and primate ecology in Kibale National Park, Uganda.

- Addressed three main questions: 1) what is the relationship among weather variables at this research site? 2) Which variables most closely influence fruit production? 3) What is the temporal pattern of fruit shortfalls and high-production events?

- Used basic exploratory analyses, linear regression models, and generalized additive models

- Primary findings: 1) Fruit production has increased over the 20 years of the study, 2) seasonality in fruiting was relatively weak over the course of the study, 3) productivity increased with decreasing average temperature, 4) periods of fruit shortfall have become more common over the course of the study  

- Weak seasonality and a steady increase in fruit production suggest that Kibale is a high-quality habitat for animals relying on food resources. However, average temperatures are projected to substantially increase in this region in the coming decades, and the findings of this project suggest this increase will result in reduced fruit production and, perhaps, more prolonged periods of fruit scarcity. 


**Predicting interactions between Down Syndrome and learning ability using gene expression values** 

- Down Syndrome (DS) is caused by inheritance of an extra copy of chromosome 21 (“trisomy 21”) and is associated with a host of behavioral and cognitive deficits, including a reduced ability to learn and retain new information. It is thought that these deficits are linked to the overexpression of the genes found on chromosome 21. However, we lack a sufficient understanding of which of the >500 genes on chromosome 21 are most directly linked to the learning difficulties found in DS, nor do we have a strong understanding of how DS impacts learning at the genetic level. 

-  Primary questions: 1) Which of the >500 genes on chromosome 21 are most directly linked to DS-related learning difficulties? 2) How does DS impact learning at the genetic level? 

- I addressed these issues using a [dataset](https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression) consisting of 1050 measurements of gene activity levels in 77 genes found in the brain in lab mice. 

- Used ridge classifiers, random forests, K-nearest neighbors, and classifier chain models to predict the gene-level effects of exposing mice with Down Syndrome to a learning environment, both in the presence and absence of treatment with a drug (memantine) known to rescue learning abilities in patients with related conditions (e.g., Alzheimer’s). 

- Primary finding: A ridge classifier had the highest predictive accuracy score of all models, and, surprisingly, chain classifier models performed very poorly.

- The findings of this project suggest that models can be used to identify the signatures of Down Syndrome and its related effects at the gene level, perhaps providing a pathway for the eventual production of drug treatments for DS-linked learning deficits.

**Using neural networks to predict genetic markers of Down Syndrome-associated learning deficits**

- This project builds upon the previous DS project described above. 

- Here I used a deep autoencoder neural network to “denoise” the gene activity data, then applied the same ridge regression model used in the previous project to the denoised dataset.

- I compared ridge regression results to those obtained from applying a deep sequential neural network model to the dataset. 

- Primary finding: The sequential neural network performed remarkably well (and far better than the autoencoded data run through a ridge regression) in its ability to predict the gene-level effects of Down Syndrome, as well as the effect of treatment with memantine (the drug used to rescue learning).
 
- The fact that a single model can accurately predict the gene-level signature of these traits suggests that finely-tuned drug therapies may be developed to directly target the gene activity identified by this model.
