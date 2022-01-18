# T81-552-Spring2022
Special Topics in Advanced Machine Learning

[Washington University in St. Louis](https://wustl.edu/)

Instructor: Jeromey Farmer

Spring 2022, Online, Asynchronous Course

# Course Description

Machine Learning studies representations and algorithms that allow machines to improve their performance on a task from experience. Machine learning is all about finding patterns in data to get computers to solve complex problems. Instead of explicitly programming computers to perform a task, machine learning lets us program the computer to learn from examples and improve over time without human intervention. This requires addressing a difficult question: how to generalize beyond the examples that have been provided at "training time" to new examples that you see at "test time". 

Machine learning is an exciting and fast-moving field with many recent consumer applications (e.g., Microsoft Kinect, Google Translate, iPhone's Siri, digital camera face detection, Netflix recommendations, Google news) and applications within the sciences and medicine (e.g., predicting protein-protein interactions, species modeling, detecting tumors, personalized medicine). This course builds on students’ mathematical, programming, and problem-solving skills and knowledge in the field of machine learning. Students will expand their knowledge in the theoretical foundations of machine learning and how to apply machine learning to solve new problems. 

The course will focus on the two major paradigms in machine learning - supervised and unsupervised learning.  This course will show students how generalization processes can be formalized and implemented. We will look at machine learning from many different perspectives, illustrating the key concepts in the field.  The core objective of this class is to provide a rigorous training on the fundamental concepts, algorithms, and theories in machine learning. The lectures will cover perceptron/linear models, projection/nonlinear embedding methods, Bayes methods, neural networks/deep learning, parametric/non-parametric methods, kernel machines, hidden Markov models, reinforcement learning, mixture models and graphical models.  

After successfully completing this course, students will be able to:

-	Understand key concepts in machine learning
-	Use acquired hands-on experiences with implementation of machine learning algorithms
-	Derive the mathematical formulation of the fundamental machine learning models
-	Formulate and solve application questions with appropriate machine learning methods
 

# Syllabus

Week|Content
----|----
Week 1 <br> **1/27/2021** |**Introductions** <ul><li>1.1. [Data science in practice](weekly_materials/week1/docs/data-science-in-practice.md) <li> 1.2. Introduction to Python Programming Language <ul> <li> 1.2.1. [Python introduction and set up](weekly_materials/week1/docs/python-introduction-and-set-up.md) <li> 1.2.2. [Jupyter Notebook and Lab](weekly_materials/week1/docs/jupyter-notebook-and-lab.md)  </ul> 1.3. [An introduction to Amazon Web Service (AWS)](weekly_materials/week1/docs/an-introduction-to-aws.md) </ul>**Assignment 1.1:** [Install anaconda and test Jupyter notebook](weekly_materials/week1/assignments/assignment-1.md) <br>**Assignment 1.2:** [AWS fundamentals](weekly_materials/week1/assignments/assignment-2.md) </ul>
Week 2 <br> **2/3/2021** |**Python Fundamentals** <ul><li> 2.1. [Basic data types](weekly_materials/week2/notebooks/basic-data-types.ipynb) <li> 2.2. [Data structure and iterables](weekly_materials/week2/notebooks/data-structure-and-iterables.ipynb)<li> 2.3 [Conditional, iteration, and function in Python](weekly_materials/week2/notebooks/conditional_iteration_function.ipynb)<li>2.4. [Map, filter, reduce, comprehension](weekly_materials/week2/notebooks/map-filter-reduce-comprehension.ipynb) </ul>**Assignment 2:** [Programming practice assignment](weekly_materials/week2/assignments/assignment2.ipynb)</ul>
Week 3 <br> **2/10/2021** |[**Coding Best Practices in Data Science** ](weekly_materials/week3/docs/coding-best-practices-in-data-science.md)<ul><li> 3.1. [Top-ten best-practices](weekly_materials/week3/docs/top-ten-best-practices.md) <li> 3.2. [Style guide for python code](weekly_materials/week3/docs/style-guide-for-python-code.md) <li>3.3. [Documenting python code](weekly_materials/week3/docs/documenting-python-code.md) <li>3.4. [Version control](weekly_materials/week3/docs/version-control.md) <li>  3.5. [Code linting](weekly_materials/week3/notebooks/linting.ipynb) </ul>**Assignment 3:** [Version control, project structure, and code documentation](weekly_materials/week3/assignments/assignment3.md) </ul>
Week 4 <br> **2/17/2021** |[**Modeling Overview**](weekly_materials/week4/docs/overview.md) <ul><li> 4.1. [Types of models](weekly_materials/week4/docs/types-of-models.md) <ul><li> 4.1.1. [Causal/Prescriptive/Predictive](weekly_materials/week4/docs/types-by-purpose.md) <li> 4.1.2. [Statistical vs Machine learning](weekly_materials/week4/docs/types-by-framework.md) <li> 4.1.3. [Blackbox vs Explainable](weekly_materials/week4/docs/types-by-interpretability.md) </ul> 4.2. [Model development steps](weekly_materials/week4/docs/model-development-steps.md) </ul>
Week 5 <br> **2/24/2021**| [**Accessing Data**](weekly_materials/week5/docs/retrieving-data.md) <ul><li> 5.1. [Introduction to RESTful APIs](weekly_materials/week5/docs/intro-to-web-api.md) <li> 5.2. [Interacting with API using Postman](weekly_materials/week5/docs/postman.md) <li> 5.3. [Getting data from API](weekly_materials/week5/notebooks/accessing-data-with-requests.ipynb) <li> 5.4. [Parsing JSON data](weekly_materials/week5/notebooks/parsing-json.ipynb) <li> 5.5. [Reading text files](weekly_materials/week5/docs/read-text-files.md) <li> 5.6. [Fetching data from PostgreSQL database](weekly_materials/week5/docs/accessing-data-from-postgres.md) </ul> **Assignment:** Finalization of final project topic and data set (Not graded)</ul>
Week 6 <br> **3/3/2021**| **Numpy/Pandas for Data Wrangling** <ul><li> 6.1. [Numpy data structure](weekly_materials/week6/notebooks/numpy-data-structure.ipynb) <li> 6.2. [Numpy functions](weekly_materials/week6/notebooks/numpy-functions.ipynb) <li> 6.3. [Vectorization](weekly_materials/week6/notebooks/vectorization.ipynb) <li> 6.4. [Pandas basics](weekly_materials/week6/notebooks/pandas-basics.ipynb) <li> 6.5.[Data manipulation with Pandas](weekly_materials/week6/notebooks/data-manipulation-with-pandas.ipynb) <li> 6.6. [Vizualization in Pandas](weekly_materials/week6/notebooks/pandas-vizualization.ipynb) </ul> **Assignment 4:** [Exercise with Numpy and Pandas](weekly_materials/week6/assignment/assignment4.ipynb) </ul>
Week 7 <br> **3/10/2021**| **Exploratory Data Analysis (EDA)** <ul><li> 7.1. [Introduction to EDA](weekly_materials/week7/docs/eda.md) <li> 7.2. [Univariate analysis](weekly_materials/week7/notebooks/eda-univariate.ipynb) <li> 7.3. [Bivariate analysis](weekly_materials/week7/notebooks/eda-bivariate.ipynb) <li> 7.4. [Temporal analysis](weekly_materials/week7/notebooks/temporal-eda.ipynb) <li> 7.5. [Spatial analysis](https://nbviewer.jupyter.org/github/abanskota/t81_577_data_science/blob/master/weekly_materials/week7/notebooks/geo-visualization-folium.ipynb) </ul> **Assignment 5:** [Vizualization and data summary](weekly_materials/week7/assignment/assignment5.md) </ul>
Week 8 <br> **3/17/2021**| [**Data Preprocessing**](weekly_materials/week8/docs/preprocessing.md) <ul><li> 8.1.[Scikit-learn preprocessing](weekly_materials/week8/docs/intro-to-scikit-learn.md)<li>8.2. [Missing value treatments](weekly_materials/week8/docs/missing-value.md) <li> 8.3. [Standardization and Binning](weekly_materials/week8/docs/std-bin.md) <li> 8.4. [Categorical encodings](weekly_materials/week8/notebooks/categorical-encoding.ipynb) <li> 8.5. [Resampling](weekly_materials/week8/notebooks/resample.ipynb) <li> 8.6. [Feature engineering](weekly_materials/week8/docs/feature-engineering.md) </ul>**Assignment 6:** [Data preprocessing](weekly_materials/week8/assignment/assignment6.md) </ul>
Week 9 <br> **3/24/2021** |**Algorithms for predictive modelling- Part I** <ul><li>9.1. [Basic-modelling-terminologies](weekly_materials/week9/docs/key-terminologies.md)<li> 9.2. [linear regression](weekly_materials/week9/notebooks/linear-regression.ipynb)<li> 9.3. [Naive Bayes classification](weekly_materials/week9/notebooks/naive-bayes-classifier.ipynb) <li> 9.4. [Logistic regression](weekly_materials/week9/notebooks/logistic-regression.ipynb) <li> 9.5. [Tree based algorithms](weekly_materials/week9/notebooks/tree-based-algorithms.ipynb)<li>9.6. [K-means clustering](weekly_materials/week9/notebooks/k-means-clustering.ipynb) </ul> 
Week 10 <br> **4/14/2021** |**Algorithms for predictive modelling- Part II** <ul><li>10.1. [Support vector machine](weekly_materials/week10/notebooks/support-vector-machine.ipynb)<li> 10.2. [Neural Network](weekly_materials/week10/notebooks/neural-network.ipynb)<li>10.3. [Streamlining workflows with pipeline](weekly_materials/week10/notebooks/scikit-learn-pipeline.ipynb)<li>10.4. [Model Evaluation](weekly_materials/week10/docs/model-evaluation.md)</ul>**Assignment 7:** [Model Fitting and evaluation](weekly_materials/week10/assignment/assignment7.md) </ul>
Week 11 <br> **4/21/2021** | **Best practices in Machine Learning** <ul><li> 11.1. [Reducing bias and variances](weekly_materials/week11/docs/bias-variance-reduction.md) <li> 11.2. [Selecting train/dev/test dataset](weekly_materials/week11/docs/training-testing.md) <li> 11.3. [Hyperparameter tuning](weekly_materials/week11/notebooks/Hyperparameter+Tuning.ipynb) </ul> **Assignment:** [hyperparameter tuning](weekly_materials/week11/assignment/assignment8.md) </ul>
Week 12 <br> **4/28/2021** | **Deploy a Machine Learning model- Part I** <ul><li> 13.1. [Overview of model deployment](weekly_materials/week12/docs/model-deployment.md) <li> 13.2 [Basic terminologies](weekly_materials/week12/docs/terminologies.md) <li> 13.3. [Deploy a model as a Flask app](weekly_materials/week12/docs/model-as-a-service.md) </ul>
Week13 <br> **5/5/2021** |  **Deploy a Machine Learning model- Part II** <ul><li> 14.1. [Docker for data science](weekly_materials/week13/docs/docker-for-ds-.md) <li>14.2. [Introduction to Airflow](weekly_materials/week13/docs/airflow.md) </ul> **Assignment:** Final project due on April 30 </ul>
