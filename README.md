<h1 style='text-align:center'>Predicting the probability of heart disease: A study based on personal keys<h1>

## Table of Contents
* [Introduction](#chapter1)
    * [Where is this data set coming from?](#section_1_1)
    * [Dataset Link](#section_1_2)
* [Objective](#chapter2)
* [Import Libraries & Data Collection](#chapter3)
* [Split Data](#chapter4)    
* [Data Exploration](#chapter5)    
    * [Missing Data](#section_5_1)
    * [Explanation of column name](#section_5_2)
    * [Numerical Features Analysis](#section_5_3)
    * [Categorical Features Analysis](#section_5_4)
* [Data Preparation](#chapter6)    
    * [Remove Outliers](#section_6_1)
    * [Transform Numerical Data](#section_6_2)
    * [Transform Categorical Data](#section_6_3)
* [Model Train & Select](#chapter7)                    
    * [Cross-Validation on Selected model](#section_8_1)
    * [Tune Hyperparameters for Model](#section_8_2)
* [Model Save](#chapter9)                

   
 ## Introduction  <a class="anchor" id="chapter1"></a>
<p>According to the CDC, heart disease is one of the leading causes of death for people of most races in the US (African Americans, American Indians and Alaska Natives, and white people). About half of all Americans (47%) have at least 1 of 3 key risk factors for heart disease: high blood pressure, high cholesterol, and smoking. Other key indicator include diabetic status, obesity (high BMI), not getting enough physical activity or drinking too much alcohol. Detecting and preventing the factors that have the greatest impact on heart disease is very important in healthcare. Computational developments, in turn, allow the application of machine learning methods to detect "patterns" from the data that can predict a patient's condition.</p>

#### Where is this data set coming from? <a class="anchor" id="section_1_1"></a>
<p>Originally, the dataset come from the CDC and is a major part of the Behavioral Risk Factor Surveillance System (BRFSS), which conducts annual telephone surveys to gather data on the health status of U.S. residents. As the CDC describes: "Established in 1984 with 15 states, BRFSS now collects data in all 50 states as well as the District of Columbia and three U.S. territories. BRFSS completes more than 400,000 adult interviews each year, making it the largest continuously conducted health survey system in the world.". The most recent dataset (as of February 15, 2022) includes data from 2020. It consists of 401,958 rows and 279 columns. The vast majority of columns are questions asked to respondents about their health status, such as "Do you have serious difficulty walking or climbing stairs?" or "Have you smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes]".</p>

#### Dataset link <a class="anchor" id="section_1_2"></a> 
<a href='https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease'>https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease</a>

