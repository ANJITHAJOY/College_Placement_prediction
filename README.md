# Web Appalication to Predict College_Placement_prediction

#### The DataSet Contains Various Features Like Stream Of the Students to be Placed ,Age from 19 to 30, Number of Internship a Student has , CGPA , Gender etc For the Prediction.
We Peformed Basic EDA to get Some Insight from the data.
## <b>--> EDA :</b>
### Gender :

![image](https://user-images.githubusercontent.com/25205826/132099743-887b54fb-047c-4434-9535-5b06cf757680.png)

From The Graph We Can Say That Number of Males Are More than Female For Placements.

### Number of Students in Each Stream For Placements :

![image](https://user-images.githubusercontent.com/25205826/132099840-def953a6-e1ed-42ac-a172-a32ce0821948.png)

We can See that for placements Students From Computer Science And IT are More than And Other Stream.

### Placement :

![image](https://user-images.githubusercontent.com/25205826/132099943-dfd3f647-91ac-483f-973e-99b7474ba201.png)

From The Graph We can that that Students From Computer Science and It Has More Chance of Getting Placed Than Any Other Steam.

### For Prediction We have Used two Machine Learning Classification Algroithm.
## 1. Logistic Regression.
                    After Training the Algorithm .The Accuracy of Logistic Regression on Test Data is 76%.
  ## Auc-RocCurve:-
  ![image](https://user-images.githubusercontent.com/25205826/132100145-29111d0f-e0cb-4aae-a749-c0f32bfdf748.png)
  
## 2. Decision Tree.
                  After Training Decision Tree. The Accuracy of Decision Tree We got is 87%.
  ## Auc-RocCurve:-                  
  ![image](https://user-images.githubusercontent.com/25205826/132100191-9dc8ad62-0ea4-45a0-9e93-c5a84f000835.png)
  
  Thus We can use Decision Tree For Prediction.
  
 ### Lets Prediction:
                Val = [[30,0,8,0,0,1,5]]
                DT_model_full.predict(Val)
 #### Output:
                [1]
 
 Here 30 is Age , We Enter 0 As Number of Internship, CGPA is 8 , Hostel as 0	, History Of Backlogs as 0, gender as 1 i.e Male and stream as 5 i.e Mechanical Engineering Stream and got the output of 1 Which is Placed.

## Lets See it in Web Page :-

![image](https://user-images.githubusercontent.com/25205826/132132063-c78561c9-0ba4-40a6-b696-50798bcd180f.png)

### We here Entered Age , Internship ,Cgpa ,backlogs ,Gender and Stream and the Model Predicted that the Student Will be Predicted.
