# ML_End_to_End_project_WaferFault_Detection
Full stack ML project with end to end pipeline. Detailed Design document also attached. 

Problem Statement													
To build a classification methodology to predict the quality of wafer sensors based on the given training data.													
![image](https://user-images.githubusercontent.com/52264008/123025496-addf6f80-d3a8-11eb-97c5-89da925d608a.png)




![image](https://user-images.githubusercontent.com/52264008/123001379-a7d49900-d37e-11eb-9643-2707cafec93d.png)


Clustering	kneed import KneeLocator - for KMeans
Models	XGBoost and RandomForest with HyperParameter tuming trained for each cluster and best model with best parameters are choosen for each cluster 
	
	Feature Engineering
Scaling	Standard Scaler
String operation	String operation on specific column
Impute Missing values	KNN Imputer
	
	
	Training Model Stack
Kmeans	Clsuter the data
Models	Train each group of models for each cluster and save the best performing model for each cluster
	
	Prediction Model Stack
Kmeans	Cluster the data
Model	Use the respective best saved model for each cluster to predict
![image](https://user-images.githubusercontent.com/52264008/123025421-986a4580-d3a8-11eb-9830-6021d5f062cc.png)

