# 2401FTDS_Unsupervised-Learning-Project-Team-EG3

# Anime Recommender Systems<div id="main image" align="center">
<div id="main image" align="center">
  <img src="https://github.com/justin9503/2401FTDS_Unsupervised-Learning-Project-Team-EG3/blob/main/anime.webp" width="700" height="500" alt=""/>
</div>
 
## Table of contents
* [1. Project Overview](#project-description)
* [2. Dataset](#dataset)
* [3. Packages](#packages)
* [4. Environment](#environment)
* [5. MLFlow](#mlflow)
* [6. Streamlit](#streamlit)
* [7. Team Members](#team-members)

## 1. Project Overview <a class="anchor" id="project-description"></a>

In the era of digital streaming, the sheer volume of available anime content can be overwhelming for viewers seeking new series to watch. An anime recommendation system is designed to address this challenge by leveraging data science and machine learning techniques to provide personalized anime suggestions tailored to individual preferences. This project aims to develop an advanced recommendation system that enhances user experience by accurately predicting and suggesting anime series that users are likely to enjoy.

Objectives:

* Data Collection and Preprocessing:

Gather a comprehensive dataset of anime series, including features such as genres, ratings, user reviews, and watch history.
Preprocess the data to handle missing values, normalize ratings, and prepare it for model training.

* Exploratory Data Analysis (EDA):

Perform EDA to uncover patterns, trends, and insights within the dataset.
Visualize the distribution of genres, popular anime series, and user rating behaviors.

* Model Development:

Implement various recommendation algorithms, including collaborative filtering, content-based filtering, and hybrid models.
Use matrix factorization techniques like Singular Value Decomposition (SVD) to improve the accuracy of collaborative filtering models.

* Evaluation and Optimization:

Evaluate the performance of the recommendation models using metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).
Optimize the models through hyperparameter tuning and cross-validation to enhance recommendation quality.

* Deployment:

Develop a user-friendly web application using Streamlit to allow users to interact with the recommendation system.
Deploy the web application on a cloud platform to ensure scalability, reliability, and ease of access for users.
Implement continuous integration and continuous deployment (CI/CD) pipelines to automate the build, test, and deployment processes.

Impact:
This anime recommendation system aims to streamline the content discovery process for anime fans, reducing the time spent searching for new series and increasing user engagement. By delivering personalized recommendations, the system can enhance user satisfaction and contribute to the growth of the anime community.

With the successful implementation of this project, users will have access to a powerful tool that not only enriches their viewing experience but also introduces them to a diverse range of anime content they might otherwise miss.

## 2. Dataset <a class="anchor" id="dataset"></a>

Data Overview:

This dataset contains information on anime content (movies, television series, music, specials, OVA, and ONA*), split between a file related to the titles (anime.csv) and one related to user ratings of the titles (training.csv). The test.csv file will be used to create the rating predictions.

*OVA: Original Video Animation - anime film / series made for release in home-video formats, ONA: Original Net Animation is an anime that is directly released onto the Internet.
You can find both the `train.csv` and `test.csv` datasets [here](https://www.kaggle.com/competitions/anime-recommender-system-project-2024/data).

Supplied files:
  
- anime.csv: This file contains information about the anime content, including aspects such as the id, name, genre, type, number of episodes (if applicable), an average rating based on views, and the number of members in the anime 'group'.
- train.csv:This file contains rating data, supplied by individual users for individual anime titles. It contains user_id information, the anime_id of the title watched, and the rating given (if applicable).
- test.csv: This file will be used to create the final submission. It contains a user_id and an anime_id column only - no rating (that's your task!). These ids will be used to create the rating predictions.

## 3. Packages <a class="anchor" id="packages"></a>

To carry out all the objectives for this repo, the following necessary dependencies were loaded:

- Programming Languages: Python, JavaScript
- Machine Learning Libraries: Scikit-learn, TensorFlow, Keras
- Data Processing: Pandas, NumPy
- Database: PostgreSQL, MongoDB
- Deployment: Streamlit, AWS

## 4. Environment <a class="anchor" id="environment"></a>

It's highly recommended to use a virtual environment for ones projects, there are many ways to do this. Make sure to regularly update this section. This way, anyone who clones the repository will know exactly what steps to follow to prepare the necessary environment. 

## 5. MLFlow<a class="anchor" id="mlflow"></a>

MLOps, which stands for Machine Learning Operations, is a practice focused on managing and streamlining the lifecycle of machine learning models. The modern MLOps tool, MLflow is designed to facilitate collaboration on data projects, enabling teams to track experiments, manage models, and streamline deployment processes. For experimentation, testing, and reproducibility of the machine learning models in this project, we will use MLflow. MLflow will help track hyperparameter tuning by logging and comparing different model configurations. This allows one to easily identify and select the best-performing model based on the logged metrics.

- Please have a look here and follow the instructions: https://www.mlflow.org/docs/2.7.1/quickstart.html#quickstart

## 6. Streamlit<a class="anchor" id="streamlit"></a>

### What is Streamlit?

[Streamlit](https://www.streamlit.io/)  is a framework that acts as a web server with dynamic visuals, multiple responsive pages, and robust deployment of your models.

In its own words:
> Streamlit ... is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!  All in pure Python. All for free.

> It’s a simple and powerful app model that lets you build rich UIs incredibly quickly.

[Streamlit](https://www.streamlit.io/)  takes away much of the background work needed in order to get a platform which can deploy your models to clients and end users. Meaning that you get to focus on the important stuff (related to the data), and can largely ignore the rest. This will allow you to become a lot more productive.  

##### Description of files

For this repository, we are only concerned with a single file:

| File Name              | Description                       |
| :--------------------- | :--------------------             |
| `base_app.py`          | Streamlit application definition. |


## 7. Team Members<a class="anchor" id="team-members"></a>

| Name                                                                                        |  Email              
|---------------------------------------------------------------------------------------------|--------------------             
| [Justin Ndivhuwo Tshifaro](https://github.com/justin9503)                                                | JustinNdivhuwoTshifar@gmail.com
| [Mahlatse Hunadi Masemola](https://github.com/MahlatseMasemola)                                                                                  | MahlatseMasemola@gmail.com
| [Zwiitwaho Mugodo](https://github.com/ZweeteM)                                                                            | mugodozwiitwaho@gmail.com
| [Mbalenhle Lenepa](https://github.com/Mbali0901's)                                                | lenepembali@gmail.com
| [Lungile](https://github.com/LFBaloyi19)                                       | lungile@gmail.com

