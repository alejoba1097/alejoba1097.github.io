# Data Science - Data Engineering - Machine Learning - MLOPs

# Questions/To-Do

- Do we want to add absolutely everything we know here, or only what we want to showcase?
- What order to have for the projects? I think the first ones should be what we actually want to showcase (Deep Learning and MLOps)
- Let's use non-structured data for all the projects. This might help to showcase embeddings to vectorize the data. Use vector database. This would make both computer vision and deep learning transversal to all the projects
- Make sure that the projects are divided by tasks, instead of methods
- Let's define a dataset and perform several algorithms to it. Each repository should be named according to the dataset, and implement all of the methods accordingly
- Explain difference between task, model, dataset and cost function, and present each project with such characteristics
- Add projects that have been developed during our work experience in the work experience section, even if we don't mention specifics due to NDA

# Education

# Work Experience

# Languages

# Skills (Make 2 columns)
## Hard skills
- Python
- SQL
- NoSQL (Which ones (?))
- Spark (PySpark)
- AWS (What services exactly)
- CI/CD (?)

## Soft skills
- Analysis
- Leadershiip


# Projects

In this section, I showcase how to approach different tasks for current ML applications, using the different methods that are out there.


## Master's Thesis

## Supervised Learning:
REMEMBER TO CHANGE ALL THE NAMES TO THE PROJECT ITSELF, NOT THE TASK

### Regression
Task: Regression
Dataset:
Models:
- Linear Regression
- Ridge, Lasso and Elastic Net Regularization
- Feature selection: hypotesis tests, forward and backward search, random search, etc.
- Nadaraya-Watson (?)
- PCA somewhere (?)
- Deep Learning
Cost function:


### Classification
Most likely, we're going to use a representation of something not structured. Classical algorithms are meh nowadays
- Logistic Regression
- Naive Bayes
- kNN: different distances (Mahalanobis, robust Mahalanobis euclidean, etc.)
- SVM
- Random Forest
- XGBoost
- Deep Learning

### Time series (?)
- Exponencial Smoothing
- ARIMA
- Prophet
- Loss Functions (Hilber and that stuff)

## Unsupervised Learning
For this one, we could use the credit fraud detection (anomaly detection)

- kMeans: Use different metrics
- PCA for dimensionality reduction
- Something from non-parametrics statistics (depth measures. This could be the objective of the whole project, put to test the depth in comparison to the classical methods)
- Random Forest
- Hierarchical Clustering (maybe)
- DBScan

## NLP - Data Mining
Recommendation System for movies, books, products. Define the dataset, it would be nice to use a scraping bot or something like that, and recommend interesting products or something else

Ideas: careers to choose, scientific papers to read, products to buy, etc.

This would be nice to be done with Spark, to showcase data mining

- TF-IDF
- Hashing table
- LLM (?)

## Reinforcement Learning
The reactor would be nice, if we're able to simulate it better and improve the model. Otherwise, look for another dynamic system and control it (I love that application)
- Try different methods, but obviously using deep learning. I don't want to use tables with space-states
- Deterministic for this case would be better
- Policy defined by a neural network
- Inputs as the variables and outputs as the actions to be taken in the system

## Evolutionary Learning
- The sudoku project, but of course, but expanding it to $n \times n$

## Computer Vision (?)
- LSTM vs Transformer but from scratch
- Classify images/video/audio. What if this is the project for Supervised Learning instead?

## Generative AI
What do we want to generate? It would be nice to do something with different data types (multimodal): given an image, text, audio or video, generate something
- Autoencoders
- LLMs
- RAG
- LSTM/Transformers, or something from scratch (?) Take something from the books and apply it

## MLOps and Production Deployments
- MLFlow. Not going to use it for the rest of the projects, tbh
- CI/CD with Github actions/Jenkins
- Docker images
- Kubernetes
- Airflow (?)
- DVC
- Pytest (unit tests, integration tests, load tests)
- Data Engineering

## Data Engineering
ETL with something, anything, it doesn't matter what