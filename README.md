# Early-stage-diabetes-predictions
code google colab link:https://colab.research.google.com/drive/1wlr7ZlMmzhkJVmE1Ss2H9ZBPp5UPBShA?usp=sharing

code deployed from azure machine learning studio-compute-jupyter lab notebook-download link-https://mlproj.centralindia.instances.azureml.ms/files/Early_stage_Diabetes_Prediction%20git.ipynb?_xsrf=2%7C10def47d%7C53f16bcad13a3b13738b02c1549d689f%7C1643643614
code sharable link from azure:https://mlproj.centralindia.instances.azureml.ms/lab/tree/Early_stage_Diabetes_Prediction%20git.ipynb

.ipnb notebook has been created in two different ways-1)azure machine learning studio-notebooks(as shown in demo video)
                                                      2)azure machine learning studio-compute-jupyter lab(download link is available above '3rd'point )
                                                      
what each line of code does can be seen in main 'early stage diabetes prediction.ipnb'

documentation op project:https://docs.google.com/document/d/1OVxTWgmeCL9ejNm_oQ41SrY7vD0IdB3K/edit?usp=sharing&ouid=103684182816238173927&rtpof=true&sd=true

summary:

Azure Machine Learning studio is a web portal in Azure Machine Learning that contains low-code and no-code options for project authoring and asset management. If you're a new user, choose Azure Machine Learning, instead of ML Studio (classic).
my project is created in this above mentioned service,it was easy and not more time comsuming while executing each cell.
my project takes huge amount of data related to diabetes and anal
project abstract:
Diabetes is a worldwide health problem that usually lasts a patient's entire life. Diabetes is a disease that affects people of all ages. Technology development is a novel technique to predicting diabetes and providing more accurate and efficient results. The majority of the studies have been conducted to predict diabetes, and the majority of the researchers have used the Pima Indian dataset. In this research, the authors develop a framework for estimating the chance of diabetes in patients with the greatest accuracy. In this research, the authors develop a framework for estimating the chance of diabetes in patients with the greatest accuracy. As a result, the authors want to employ a Machine Learning method can diagnose diabetes in its early stages, such as Decision Trees, SVM, and Naive Bayes Although these algorithms are used to forecast diabetes in order to save time and achieve accurate results, the Pima Indian Diabetes that are received from the UCI library test to measure.

Dataset discription:

1. Age: Age in years 
2. Gender: Male / Female
3. Polyuria: Yes / No
4. Polydipsia: Yes/ No
5. Sudden weight loss: Yes/ No
6. Weakness: Yes/ No
7. Polyphagia: Yes/ No
8. Genital Thrush: Yes/ No
9. Visual blurring: Yes/ No
10. Itching: Yes/ No
11. Irritability: Yes/No
12. Delayed healing: Yes/ No
13. Partial Paresis: Yes/ No
14. Muscle stiffness: yes/ No
15. Alopecia: Yes/ No
16. Obesity: Yes/ No
Class: Positive / Negative
Polyuria is a condition in which the body urinates more frequently than usual and passes abnormally large amounts of urine each time. Polyuria is described as the passing of huge amounts of urine often - more than 3 litres per day compared to the usual daily urine output of 1 to 2 litres in adults.
Polydipsia is the medical term for being extremely thirsty. Polydipsia is frequently associated with urinary disorders that induce frequent urination. This can cause your body to feel compelled to replace the fluids lost through urination on a regular basis. Physical factors that cause you to lose a lot of fluid can also cause it.
Candida causes genital thrush (or candidiasis), which is a common yeast infection. It primarily affects the vaginal area, but it can also impact the penis, and it can be uncomfortable and painful. Many different varieties of yeast and bacteria thrive in the vaginal area naturally and rarely create concerns.
Partial Paresis is a type of partial paresis that occurs when The weakening of a muscle or group of muscles is known as paresis. Partial or moderate paralysis is another name for it. Paresis, unlike paralysis, allows people to move their muscles. These movements are simply less powerful than usual.
The medical term for excessive or extreme hunger is polyphagia, often known as hyperphagia. It's not the same as having an increased appetite after exercising or engaging in other forms of physical activity. Polyphagia will not go away if you eat more food, even if your hunger level returns to normal after eating.
Alopecia Areata is a condition that causes hair to fall out in small patches, which can be unnoticeable.

Problem Identification & Objectives:

Because diabetes is a common disease with subtle early signs, a reliable method of prediction will aid patients in self-diagnosis. Different sorts of data are collected from patients to diagnose the disease, such as insulin, age, BMI, blood glucose level, family history of diabetes, and so on. A doctor is then consulted.  After that, the doctor made a decision based on his existing knowledge and expertise. This detection method, on the other hand, is frequently the most cost-effective and, on occasion, the most expensive. As a result, most patients will not receive a diagnosis right away. Early signs of start aren't always clear, which might lead to missed diagnoses and treatment delays. High blood sugar levels for an extended period of time can cause chronic damage and dysfunction in a variety of organs, including the eyes, kidneys, heart, blood vessels, and nerves. As a result, diabetes prediction at an early stage is critical. The goal of this research is to create a system that can accurately predict diabetes in a patient in the early stages.

Used methadologies:

Importing the Dataset 

Data Prepossessing
Data Transformation
(Encoding)
Finding Correlation blw Variables
Finding Feature Scores
Visualization of Data
Splitting the dataset
classificaion and prediction


Conclusion and Future Scope:

An efficient diabetes prediction model will help doctors make accurate diagnoses and help patients get timely treatment. We conduct descriptive statistics for diabetes risk prediction dataset to investigate the variables which influence the diabetes. We build diabetes prediction models based on six machine learning models including logistic regression, support vector machine, decision tree, random forest, KNN and Naive Bayes, and test error are listed. 
For the first three models, logistic regression, SVM and decision tree are simple and intuitional, and it has lower accuracy than the last three models which are more complex. As we can see, the more complex the model is, the test accuracy is higher. In the Future, we can try models which have better learning and adaptive ability and use more variety of datasets to improve the prediction accuracy.
This model can be further improved by taking various other symptoms to further enhance the rate predicting the diabetes early stage and also try other classification algorithms and further this model can be used for any further research for chronic diabetes and also we can further improve this work by adding their lifestyle habits their eating habits which would further improve the predictability of diabetes in early stage  
This model can be also trained with the lifestyle, eating and living habits of healthier sections of the population whose habits can be analyzed by the model and once the model is trained then after the diagnosis of a person the model can accurately guide the person with a good set of lifestyle habits to lead a healthy life just by implementing a few specific lifestyle changes and eating habits. Thus this model can be successfully used in the medicine sector, not just in the form of educative medicine, also preventive medicine as the model will be successfully able to predict future diagnosis and also provide advice on minor changes of lifestyle that could help a person to avoid those diseases in their life.


