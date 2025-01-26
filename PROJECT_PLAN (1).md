## Step 3: Implement a Machine Learning Model

- Create a sub-project named `housing-model` and initialize a Python environment and dependency manager (by using Poetry and/or pyenv for example).
- Download the full housing dataset: https://www.kaggle.com/api/v1/datasets/download/camnugent/california-housing-prices.
- Analyze the data:
  - Explore relationships between variables.
  - Process data (nan, outliers, ...).
- Implement a script to train a machine learning model that will predict `median_house_value`.
- Create an API that compute a prediction.
- Find a way to dockerize the model inference API using the image name `housing-model`.
