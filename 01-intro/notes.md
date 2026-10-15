## 1.1 Introduction to Machine Learning

**In one sentence:** This was an introduction into what Machine Learning is and how it is used in everyday lives.

**Key points:**
- Machine Learning can be used to successfully replace experts with machine learning algorithms.
- Once the algorithms are in place, our model can learn patterns through historical data and we can replace the expert's experience through training the model to seek out particular patterns.
- When training the model, we usually have features (characteristics and factors we know of the object/situation) and target (what we want to predict). After training the model, we use the model to predict the target by only giving it the features and letting it produce the target.

**Example:** Car price prediction for users wanting to sell their cars.

**Still unsure about:** Nothing yet.

## 1.2 ML vs Rule-Based Systems

**In one sentence:** This lesson was a breakdown of the difference between ML and rule-based systems, what both these systems have to offer and how to use these systems.

**Key points:**
- Rule-Based systems consist of rules written as code manually by a human. So if certain features are flagged by this system, rules are applied and an outcome comes out.
- Machine learning systems consist of data, the outcomes and after the training has been concluded we are left with the model that predicts the outcomes from its training.
- Rule-Based systems are useful in their own particular manner but it has its flaws. This system tends to need constant rule additions and is hard to maintain as patterns change. Machine Learning learns the rules from examples and applies it to get the outcome.

**Example:** Email spam detector

**Still unsure about:** Classification of features and prediction outputs.

## 1.3 Supervised Machine Learning

**In one sentence:** This lesson explained what supervised machine learning is and how the data is organised when we train a model.

**Key points:**
- Supervised machine learning is when we train a model on examples that include the correct answers, so it learns the link between the features and the target and can predict the target for new data.
- The features of all our examples are stored in a feature matrix, where each row is one example and each column is one feature, and the target is stored separately with one value per row.
- There are three types of supervised learning: regression (predicting a number), classification (predicting a category) and ranking (ordering items).

**Example:** Car price prediction (regression) and email spam detection (classification).

**Still unsure about:** Nothing yet.

## 1.4 CRISP-DM

**In one sentence:** This lesson was an explanation of CRISP-DM, a process used to organise a machine learning project from understanding the problem through to deployment.

**Key points:**
- CRISP-DM has six steps which are business understanding, data understanding, data preparation, modeling, evaluation and deployment. In business understanding we set a measurable goal and ask whether we actually need machine learning.
- In data understanding we check that we have enough good data, in data preparation we clean it and turn it into a table of features and a target, and in modeling we train different models and choose the best one.
- Evaluation checks whether the goal has been reached and deployment rolls the model out to all users, often by testing it on a small group first. Machine learning projects need many iterations, so we start simple, learn from the feedback and improve.

**Example:** Email spam detector

**Still unsure about:** Nothing yet.

## 1.5 Model Selection Process

**In one sentence:** This lesson explained how we compare different models and select the best one, and how splitting the data into train, validation and test makes sure the model didn't just get lucky.

**Key points:**
- We train different models such as logistic regression, decision tree, random forest and neural network, then compare their accuracy on the validation set, which is data the models were not trained on. The best accuracy wins, so in the lesson's made-up example the neural network at 80% was selected.
- A model can get lucky on the validation set, which is the multiple comparisons problem. In the coin example, one coin guessed the whole validation set correctly by chance, and a separate test set protects us from this.
- We split the data into train, validation and test (e.g. 60%, 20% and 20%), train the models, evaluate them, select the best model, apply it to the test set and compare the validation and test performance. If the two are close, the model really does behave well.

**Example:** Comparing coins as spam detectors, where one coin got lucky and scored 100%.

**Still unsure about:** Nothing yet.

## 1.6 Setting up the Environment

**In one sentence:** This lesson showed how to set up the environment for the course, with GitHub Codespaces as the recommended option and local setups as alternatives.

**Key points:**
- The course needs Python, NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn and Jupyter notebooks, which are installed with pip (e.g. `pip install jupyter numpy pandas scikit-learn seaborn`).
- GitHub Codespaces gives a ready-made remote environment in the browser or in VS Code, while the alternatives are a local setup, Anaconda, the cloud or notebook services like Kaggle and Colab.
- I set up locally in VS Code with a virtual environment (`.venv`), installed the packages with pip, and saved them to `requirements.txt`.

**Example:** Creating a `01-intro` folder with a notebook and running `import pandas as pd` to check that everything works.

**Still unsure about:** Nothing yet.