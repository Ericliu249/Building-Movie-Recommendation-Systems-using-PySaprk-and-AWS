# Building-Movie-Recommendation-Systems-using-PySaprk-and-AWS

- Author:Yang Liu, Jiawei Xue, Shuqiong Chen, Ashish Negi<br>
- Contact: eric.liu.249@gmail.com, yliu249@stevens.edu 

## Abstract
In this project, we built a collaborative filtering recommendation system using PySpark and Alternating Least Squares (ALS) algorithm. Specifically, we built a model-based collaborative filtering system that issues recommendations of movies based on the relationship between queried user and movie and the rest of the rating matrix. We used the root of the mean square error (RMSE) as our model evaluation metrics and compared the model result in different data scale and different platform. The result turned out that the local, HFSC Cluster and Amazon Web Service (AWS) works well when reducing the RMSE as the scale increased, while local perform better than HFSC Cluster when comparing the runtime of the ALS building process. Finally, we improve the ALS model runtime performance utilizing the AWS.
