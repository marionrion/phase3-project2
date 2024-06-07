## Tanzania Water Project: A Data Science Approach to Mining the Water Table
## By Marion Achieng Otieno
![image](https://github.com/marionrion/phase3-project2/assets/162312622/39c8438d-ef73-4ddf-94f8-a451e3bf27b1)
### Business Understanding:
### Overview
Tanzania faces a water crisis, with millions lacking access to safe drinking water due to malfunctioning water points. This project aims to use machine learning to predict water point functionality, helping prioritize maintenance and improve water security. By analyzing data on pumps, location, and management, the project will create a model to categorize water points as functional, needing repair, or non-functional. This information can be used to target maintenance efforts, perform preventive maintenance, and improve resource management, ultimately leading to better public health and well-being in Tanzania. The project's success hinges on accurately predicting water point functionality, categorized as fully functional, partially functional (needs repair), or non-functional.

### Research Questions:
Can machine learning models accurately predict the functionality of water points in Tanzania?
What data points are most relevant for predicting water point functionality (e.g., pump type, installation age, location, management practices)?
How can the project's water point functionality categories (functional, needs repair, non-functional) be most effectively used to improve water resource management and ensure water security in Tanzania?

### Data understanding
This dataset describes water points in Tanzania, containing information about their functionality, location, construction, management, and water characteristics. Each data point details aspects like total static head (available water), installation date, funding source, GPS coordinates, well name, population served, construction year, extraction type (e.g., manual pump), management style, and water quality. The data comes from four CSV files: train.csv (labeled data for model training), test.csv (unlabeled data for prediction), train_labels.csv (labels for the functionality of water points in train.csv), and SubmissionFormat.csv (format for submitting predictions).
### data engineering, modelling and conclusion
This project aims to predict the functionality of water pumps in Tanzania. Using Google Colab and Jupyter notebooks with tools like NumPy, pandas, and scikit-learn, it explores data (identifying missing values and encoding strategies), preprocesses it (addressing missing values, combining datasets, and applying various techniques), builds and optimizes models (experimenting with different models and hyperparameters), and achieves a best model score of 0.9539, indicating high accuracy in classifying pumps as faulty, functional, or broken.













