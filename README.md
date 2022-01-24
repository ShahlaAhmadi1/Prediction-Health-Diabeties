# Prediction-Health-Diabeties
###
### work flow:
#### 1- import libraries
#### 2- loading dataset to a dataFrame
#### 3-seperate data to data and labels
#### 4- data standardization  ====> scaler= StandardScaler()====>scaler.fit(x)===>scaler.transform(x)
#### 5-split data to train and test
#### ===>X_train, X_test, Y_train,Y_test= train_test_split(X,Y,test_size=0.2,stratify=Y,random_state=2)
#### 6- Training the model 
#### ====>classifier=svm.SVC(kernel='linear') ======>classifier.fit(X_train,Y_train)
#### 7- Prediction
#### 1. inputdata numpy as array=np.asarray(inputdata)
#### 2.Reshape ====> .reshape(1,-1)
#### 3.normalization =====>scaler.fit(inputdata_reshape)=====> scaler.transform(inputdata_reshape)
#### 4. prediction====>classifier.predict(norm_dataset)
