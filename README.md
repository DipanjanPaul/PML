PML
===

This project develops a machine learning model to identify the various exercise patterns utilizing the Human Activity Reporting Data (HAR) provided by http://groupware.les.inf.puc-rio.br/har. 

The model utilizes Random Forest for classification. The training data was split into a 70-30 ratio for training and cross validating the model. the training and cross validation errors can be seen at the bottom of each report respectively.

It was also found that only 17 feature activiely participated in determining the clusters. Hence the final model has been trained with 17 features only. 

This repositoty contains the various components and reports generated during this project. The following is a description of all the components in this repository.

I thank the HAR group for providing the data to conduct this analysis and develop the model. The details for the HAR group can be found in http://groupware.les.inf.puc-rio.br/har

1.  PML_Project.Rmd: This contains the R code for training and testing the HAR data for developing the predictive model. This is first executed with "training=T" to generate the predictive model. This is again executed with "training=F" to test the model fit on the test data.
2.   PML_Project_Sub.Rmd: This contains the R code for predicting the classifies on the actual test set provided in this project (PML-testing.csv).
3.   PML_Project_trn.html: This contains the execution of the PML_Project.Rmd in training mode (training=T)
4.   PML_Project_tst.html: This contains the execution of the PML_Project.Rmd in testing mode (training=F)
5.   PML_Project_Submission.html: This contains the execution of the PML_Project_Sub.Rmd for predicting the test set (PML-Testing.csv) data.
