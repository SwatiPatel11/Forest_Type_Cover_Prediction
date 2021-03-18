# Forest_Type_Cover_Prediction

Problem statement:
The problem statement revolves around the need to predict the forest cover type (the predominant kind of tree cover) from strictly cartographic variables (as opposed to remotely sensed data).

It includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices.

The study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. Each observation is a 30m x 30m patch. You are asked to predict an integer classification for the forest cover type. The seven types are:

Spruce/Fir
Lodgepole Pine
Ponderosa Pine
Cottonwood/Willow
Aspen
Douglas-fir
Krummholz
About the dataset
A zipped file containing the following items is given:

train.csv
The data file train.csv contains the 9072 instances with the 56 features including the target feature.

test.csv
The datafile test.csv contains the 6048instances with the 55 features excluding the target feature.

sample_submission.csv
Explained under the Submission sub-heading

FCDataDictionary.csv
The file contains data dictionary(Dictionary explaining what each feature of the dataset means) of the forest cover dataset

forest_cover_student_template.ipynb
A template notebook explaining the task breakdown to solve the given problem statement (Learners are recommended to use it)

Submission
After training the model on train.csv data, learner has to predict the target feature of the test.csv data using the trained model. The learner has to then submit a CSV file with the predicted feature.

Sample submission file(sample_submission.csv) is given to you as a reference to the format expected when you submit

Evaluation metrics
For this particular dataset, we are using accuracy_score as the evaluation metric.

Submissions will be evaluated based on Accuracy score as per the below threshold.

Your accuracy_score score	Points earned for the Task
0.83 =< accuracy_score	100% of the available points
0.83 < accuracy_score <= 0.80	80% of the available points
0.80 < accuracy_score < 0.75	70% of the available points
accuracy_score <= 0.75	No points earned
Outcomes
The main objective of this task is to provide you with an open field where you can practise and work your way with a dataset end to end without any restrictions from our side. So feel free to try out different preprocessing and feature selection techniques and apply different models of your choice and tune them until you arrive at your best solution.

In this project, you will apply the following concepts:

EDA & Data Preprocessing
Feature Selection
Model Building and hyperparameter tuning
After completing this project, you will have a better understanding of how to how to work on a dataset end to end and the different strategies you can use to increase the evaluation metric.

Skills Covered:
Hyperparmeter Tuning
Ensemble Methods
RFE
