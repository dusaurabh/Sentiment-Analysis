# Sentiment_Analysis_with_deployment_project
This end-to-end project is used for analysis of movie review sentiment and then classify the gives review into _Positive and Negative reviews_.This model is then deploy into **AWS Sagemaker with Flask** on web. It has UI interface which takes users input and then gives the real-time results on the web.

Technologies Used:-
1) Pytorch
2) AWS Sagemaker

General outline for developing this project is
1) Download or otherwise retrieve the data.
2) Process / Prepare the data.
3) Upload the processed data to S3.
4) Train a chosen model.
5) Test the trained model (typically using a batch transform job).
6) Deploy the trained model.
7) Use the deployed model.

 The Web Application Interface Looks like:-
 ![](output/sentiment.PNG)
 
 We have then tested our model by inputing the reviews which our model correctly predicts as positive
 ![](output/sentiment_pos.PNG)
 ![](output/sentiment_pos_2.PNG)
 
 We have then tested our model by inputing the reviews which our model correctly predicts as negative
 ![](output/sentiment_neg.PNG)
