Machine Learning Project
@Author : THAMBUGALA ATHUKORALALAGE JAYANI SANDUNKA ATHUKORALA

Task : A comparative study of ML algorithms in facial emotion detection task

Readings :
	 1. https://edps.europa.eu/system/files/2021-05/21-05-26_techdispatch-facial-emotion-recognition_ref_en.pdf
	 2. https://www.kaggle.com/code/gauravsharma99/facial-emotion-recognition

Prerequisites :
	python3 Installed
	jupyter-lab Installed
	Required libraries : 
		pandas
		numpy
		matplotlib
		keras
		tensorflow
		scikit-learn

Data-Set :
	Downloaded URL : https://www.kaggle.com/aadityasinghal/facial-expression-dataset
	Saved "fer2013.csv" dataset inside the "dataset" folder
	
How to execute :
	Step 1 : Extract and Open the ML_Project folder
	Step 2 : Run jupyter-lab
	Step 3 : Open and Run "project_file_1.ipynb" file and "project_file_2.ipynb" file in jupyter-lab
	
What implementation Do :
project_file_1.ipynb
	1. Import requried libraries
	2. Load dataset
	3. Visualize data summary
	4. Preprocess data
	5. Split data
	6. Define CNN, LSTM and KNN models
	7. Train CNN, LSTM and KNN models
	8. Evaluate CNN, LSTM and KNN models
	9. Calculate accuracy, f-measure, training time and prediction time
	10. Create Confusion matrix and reports for results visualization
project_file_2.ipynb
	1. Import requried libraries
	2. Load dataset
	3. Preprocess data
	4. Define CNN, LSTM and KNN models
	5. 5-fold cross validation
		1. Split data in each iteration
		2. Train CNN, LSTM and KNN models
		3. Evaluate CNN, LSTM and KNN models
	6. Calculate avarages for accuracy, f-measure, training time and prediction time
	7. Create Confusion matrix and reports for results visualization


