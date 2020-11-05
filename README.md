# Early Stage Diabetes Risk Prediction

## Overview

Diabetes is a chronic disease that threats peoples' lives, and it leads to serious damage to the heart, blood vessels, eyes, kidneys and nerves. According to statistics, in 2019, around 463 million adults were living with diabetes that means 1 in 11 people were living in diabetes, and by 2030 this will rise to 578 million. Moreover, Diabetes caused 4.2 million deaths in 2019. Because of the presence of a long asymptomatic phase, early detection of diabetes is always desired for a clinically meaningful outcome. 1 of 2 of people suffering from diabetes are undiagnosed because of its long-term asymptomatic phase. 
Early detection and treatment of diabetes is a significant step toward keeping people with diabetes healthy. The patient data can help in building a prediction model which predict the likelihood of having diabetes. 
In this project, I will use a dataset that was collected from [UCI ML](https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.) to build a machine learning model to predict diabetes at early stage.


## Data

The [dataset](https://archive.ics.uci.edu/ml/datasets/Early+stage+diabetes+risk+prediction+dataset.) contains 16 attributes:

- Age 20-65
- Sex 1.Male, 2.Female
- Polyuria 1.Yes, 2.No.
- Polydipsia 1.Yes, 2.No.
- sudden weight loss 1.Yes, 2.No.
- weakness 1.Yes, 2.No.
- Polyphagia 1.Yes, 2.No.
- Genital thrush 1.Yes, 2.No.
- visual blurring 1.Yes, 2.No.
- Itching 1.Yes, 2.No.
- Irritability 1.Yes, 2.No.
- delayed healing 1.Yes, 2.No.
- partial paresis 1.Yes, 2.No.
- muscle stiffness 1.Yes, 2.No.
- Alopecia 1.Yes, 2.No.
- Obesity 1.Yes, 2.No.
- Class 1.Positive, 2.Negative.

## Tools

The model is built using two ways: 
- *Python*: all libraries are avilable in Anaconda.
- *RapidMiner*: data science platform.

## File Descriptions 

- `Python`
	- `diabetes_data_upload.csv`: the dataset file.
	- `Early_Stage_Diabetes_Risk.ipynb`: notebook contains the Python code of data preparation and machine learning . 
- `RapidMiner`
	- `Diabetes Repository`: RapidMiner folder respiratory.
		- `Data`: data folder.
			- `diabetes_data_upload.rmhdf5table`: data file.
		- `Process`: process folder.
			- `RF model.rmp`: the file of the model process. 
	- `Image`: 
		- `ML Process.png`: RapidMiner model process image.
	 


