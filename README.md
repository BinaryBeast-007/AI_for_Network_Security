# AI_for_Network_Security

Anomaly Detection in Network Security by AI Algorithms  
CS 433 Final Report  
Members:  

Aaryan Darad (21110001)  
Abhay Kumar Upparwal (21110004)  
Aman Singh (21110020)  
Disha Chopra (21110057)  
Under the guidance of:  
Prof. Sameer Kulkarni  

##Contents  

Overview  
Dataset  
Feature Importance for Binary Class  
Implementation of Machine Learning Algorithms  
Implementation of Neural Networks  
Comparing all methods and their accuracy  
Conclusion and Future Work   
Streamlit Video Link  

##Overview  
In this project, we explore anomaly detection in network security using various machine learning and neural network algorithms. Our investigation began with feature selection on the CIC-IDS2017 dataset but transitioned to the more manageable NSL-KDD dataset due to computational limitations. We employed Random Forest, Logistic Regression, Naive Bayes, and advanced techniques like 1D Convolutional Neural Networks (CNN) and Variational Autoencoders for anomaly detection.  

##Dataset  
We utilized the NSL-KDD dataset, comprising 125,973 stream records with 22 types of attacks. Preprocessing reduced redundant records, resulting in a well-cleaned dataset with 41,473 rows × 49 columns.  
  
##Feature Importance for Binary Class  
Random Forest Regressor was used to calculate feature importance. Important features included data transfer, connection counts, success/failure rates, and behavior of the destination host.  
  
##Implementation of Machine Learning Algorithms  
We applied Random Forest, Naive Bayes, Logistic Regression, AdaBoost, KNN, MLP, QDA, and Isolation Forest for binary classification. Results demonstrated high accuracy for Random Forest, AdaBoost, and KNN.  
  
##Implementation of Neural Networks  
1D CNN and Variational Autoencoders were implemented for binary classification. 1D CNN achieved 98% accuracy, showcasing its effectiveness in anomaly detection.  
  
##Comparing all methods and their accuracy  
Various algorithms were compared, with Random Forest, AdaBoost, and KNN achieving high accuracy. Neural networks, especially 1D CNN, also demonstrated promising results.  
  
##Conclusion and Future Work  
Ensemble methods and neural networks showed superior performance. Future work involves implementing a multi-layered hierarchical structure for improved practical applicability in real-world scenarios.  
  

Streamlit Video Link - https://ai-in-network-security.streamlit.app/  
Streamlit Video - https://drive.google.com/drive/folders/1QzMBKPM6A1o9dFjF5bA0ye31ihiJVvrn  
  
