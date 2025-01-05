# Deep-Learning-in-Recommendation-System
Use a research from Meta to know how to adopt ML
Click here for the full report : https://docs.google.com/document/d/19_Jd6AoFgGBHoHUdT4w1PnWwZxtfs2oI17K3g1MVSHA/edit?usp=sharing

----------------------------------------------------------------------------------------------------------------------------------------------------
# Part 1 - Recommendation System Explanation
A. Content filtering: Use the attributes or features of an item to recommend. 
B. Collaborative filtering: Recommend items based on preference information from many users, it will measure how similar the attributes are to each other in order to predict preference and provide recommendation.

 B-1. Memory-Based: 
 Uses historical records to calculate recommended products using mathematical statistics. There are 2 types of Memory-based, one is user based - users similar to you also purchased, and the other is item based - people who bought this product also bought.

 B-2. Model-Based:
 KNN regression and Matrix Factorization.

----------------------------------------------------------------------------------------------------------------------------------------------------
# Part 2 - Deep learning based recommender systems
A joint research analyzed by people from Duke University and Meta, has developed a new model to tackle with the common challenges of adopting AutoML in recommendation system.
>> find here for the research detail : https://paperswithcode.com/paper/towards-automated-model-design-on-recommender

#Limitation 
![image](https://github.com/user-attachments/assets/7965467f-93be-48b2-8f34-c2e4b8be90e4)

#Solutions
![image](https://github.com/user-attachments/assets/a4116fd2-e1f2-44fb-996a-299701ec66d7)

----------------------------------------------------------------------------------------------------------------------------------------------------
# Part 3 - Outcomes
1. Created a new model, NASRec, to increase performance:
--Improving model performance through NASRec, which can automatically explore the best architecture to adapt to heterogeneous data
--Reduce reliance on manual design through hypernetwork strategy.

2. Showed the progress of Weight-sharing NAS in recommender systems:
--Improve the learning efficiency and effectiveness of the model through balancing and coordinating the interactions between different operators
![image](https://github.com/user-attachments/assets/92e22161-3e67-436c-a981-a4b844c093b8)



