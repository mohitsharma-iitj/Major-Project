# Major-Project    ........   early-diabetes-classification

Link to deployed website : https://diabetes-classification-tome.onrender.com

colab python machine learning code : https://colab.research.google.com/drive/1Nv5MzBniPvS_HnMrTQaXzZLgxlnia8cW?usp=sharing

report : https://docs.google.com/document/d/1MOugw_i4p9uA70Ab7PDjjss8ntu_w0VGJz90R1rqJdo/edit?usp=sharing

Dataset Link  :   https://www.kaggle.com/datasets/andrewmvd/early-diabetes-classification

github : Here are complete detail - ( https://github.com/mohitsharma-iitj/Early-Classification-of-Diabetes )

         1.  From colab pickle, trained min max scaler (to transform the input data for applying in model.pkl) -> transform_data_of_array.pkl
         
         2.  From colab pickle, trained model( detail in report) to predict diabetes (for age 16 to 90 trained) -> model.pkl
          
         3.  To create web-app ,I used the Flask library (interact with html files and model, like intermediate) , respective code in -> app.py 
          
         4.  HTML -> To render home page and to give the output
          
         5.  requirements.txt -> to let the server know, which library should be used in advance in required format
          
         6.  procfile -> to let server know aafter installing requirement, which file to execute first.   
