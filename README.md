###***Below are brief summaries of recent projects I've been working on:***


**Temporal Fluctuation in Fruit Resource Availability in a Tropical Forest**

An understanding of the nature of temporal variability in fruit production by tropical forest trees, as well as the factors influencing productivity, can inform predictions about potential impacts of climate change on the animal populations that rely on these trees as food sources. I investigated these issues in this project using data from a site of long-term research on both plant phenology and primate ecology in Kibale National Park, Uganda. In particular, I addressed three main questions, primarily using standard linear regression techniques, as well as more specialized generalized additive models: 1) what is the relationship among weather variables at this research site? 2) Which variables most closely influence fruit production in this tropical forest? 3) What is the temporal pattern of fruit shortfalls (periods of prolonged, unusually low fruit availability) and high-production events (periods of prolonged, unusually high fruit availability). 



**Predicting interactions between Down Syndrome and learning ability using gene expression values** 

Down Syndrome (DS), which is caused by inheritance of an extra copy of chromosome 21 (“trisomy 21”), is associated with a host of behavioral and cognitive deficits, including a reduced ability to learn and retain new information. It is thought that these deficits are linked to the overexpression of the genes found on chromosome 21 – the extra copy of the chromosome, in effect, results in an overabundance of the products of these genes. However, we lack a sufficient understanding of which of the >500 genes on chromosome 21 are most directly linked to the learning difficulties found in DS, nor do we have a strong understanding of how DS impacts learning at the genetic level. These shortcomings hamper efforts to develop pharmacological treatments for DS-related learning deficits. In this project, I addressed these issues using a dataset consisting of 1050 measurements of protein expression levels (a proxy for gene activity) in 77 genes found in the brain in lab mice. I used several supervised machine learning techniques, including ridge classifiers, random forests, and K-nearest neighbors models, to attempt to predict the gene-level effects of exposing mice with Down Syndrome to a learning environment, both in the presence and absence of treatment with a drug (memantine) known to rescue learning abilities in patients with related conditions (e.g., Alzheimer’s). I found that a ridge classifier had the highest predictive accuracy score of all models.



**Using neural networks to predict genetic markers of Down Syndrome-associated learning deficits**

I build upon the previous capstone project to further investigate the ability of machine learning and deep learning models to predict, at the genetic level, problems associated with learning in individuals with Down Syndrome. Here I used a deep autoencoder neural network to “denoise” the protein expression data I used in the previous capstone project, with the idea that perhaps by removing variability in the dataset not directly related to Down Syndrome- and learning-related effects, the feature set would be more easily predicted by supervised learning models. I then took the denoised set of features and ran them through the same ridge regression model I used in the previous capstone. Finally, I compared these results with those obtained from applying a deep sequential neural network model to the protein expression data. I found that the sequential neural network performed remarkably well (and far better than the autoencoded data run through a ridge regression) in its ability to predict the gene-level effects of 1) Down Syndrome, 2) learning in individuals with Down Syndrome who have not been treated with memantine (the drug used to rescue learning), and 3) learning in DS individuals who HAVE been treated with memantine. The fact that a single model can accurately predict the gene-level signature of these traits suggests that finely-tuned drug therapies may be developed to directly target the gene activity identified by this model.
