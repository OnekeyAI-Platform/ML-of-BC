# Development of Metastasis and Survival Prediction Model of luminal and non-luminal Breast Cancer with weakly supervised learning based on Pathomics

## Abstract

Objective: Luminal and non-luminal Breast Cancer are classified according to ER immunohistochemical results of pathological sections; compared with luminal type, non-luminal type seems to be more invasive and has a poor prognosis. The pathological sections of radical specimens contain a variety of histological information related to metastasis and survival of patients. Therefore, we aim to construct a model by deep learning based on pathological image to predict the metastasis and survival of luminal and non-luminal Breast Cancer patients.
Methods: This study used pathological sections of 204 radical mastectomy specimens from January 2013 to December 2014 from the second affiliated Hospital of Medical College of Zhejiang University. 204 pathological slices were scanned and converted into whole slide imaging (WSI), and all the tumor areas were labeled manually. Then the 204 samples were divided into two groups: luminal and non-luminal group. We partitioned the whole slide images (WSI) into smaller tiles measuring 512 x 512 pixels. We assessed three networks: DenseNet121, ResNet50, and Inception_v3, then we amalgamated patch-level predictions, probability histograms, and TF-IDF features to formulate definitive patient representations. These features served as the foundational input for constructing a machine-learning algorithm for metastasis analysis and a Cox regression model for survival analysis.
Result：Our results show that the Inception V3 model shows a particularly robust patch recognition ability for ER recognition. Our pathological model shows high accuracy in predicting tumor regions. The train AUC of the Inception V3 model based on supervised learning is 0.975, which is higher than the model established by weakly supervised learning. But the AUC of the metastasis prediction in training and testing sets is higher than value based on supervised learning. Furthermore, the C-index of the survival prediction model is 0.710 in the testing sets, which is also better than the value by supervised learning.
Conclusion: We have constructed the metastasis and survival prediction model of luminal and non-luminal through deep learning, and have a good effect of predicting metastasis and survival. In addition, we find that the prediction effect of establishing metastasis and survival model in weak supervision is better than that in supervised model.

Keywords: breast cancer, pathomics, weakly supervised learning, metastasis prediction model, survival prediction model

[Power by OnekeyAI](http://medai.icu/)