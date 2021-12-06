# Classification Project MVP
## Identifying potential hotel booking cancelation

- **Goal**: The analysis is to build a meanningful predicative classification model for hotel booking system to identify the books with high risk of cancelation. Metrics of precision, reall and f1 score will be used to measure the effectiveness of the model.
-  **Process**: The dataset is obtained from [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand), which is comporised of over 119k observations and 36 columns.  The data is a mixture of quantitative and categorical features and the target is a binary value of 0 and 1, with 0 means no cancelation and 1 represents the booking is canceled.
- **Preliminary conclusions**:  The preliminary analysis uses K-near neighbors models and initial logitic model with the numerical features which shows a relationship with target values.
- **From here**: This analysis will be expanded by utilizing other models, like decsion trees, adding categorical features and adjusting hyper paramters to impove the models performace.

<img src="https://github.com/PurpleGrace/Classification_github_Hotel_Checking/blob/master/MVP/MVP_KNN_5.png" alt="KNN model with K=5">

<img src = 'https://github.com/PurpleGrace/Classification_github_Hotel_Checking/blob/master/MVP/MVP_KNN_CVwithK.png'>
