## Step 2: Dockerize the API

- Create a Dockerfile in the `housing-api` folder to containerize the API.
- Create a docker-compose.yml containing the API service and **PostgreSQL**:
  - Find a way to automatically apply the migration(s) after the initialization of the db.
  - The **PostgreSQL** data should be persistent.
  - Configure **PostgreSQL** `username`, `password`, and `database` name.
  - Mount a configuration file or set the necessary environment variables for the API.
- Build, run and test the services:

```bash
docker-compose up --build
```

## Step 3: Implement a Machine Learning Model

- Create a sub-project named `housing-model` and initialize a Python environment and dependency manager (by using Poetry and/or pyenv for example).
- Download the full housing dataset: https://www.kaggle.com/api/v1/datasets/download/camnugent/california-housing-prices.
- Analyze the data:
  - Explore relationships between variables.
  - Process data (nan, outliers, ...).
- Implement a script to train a machine learning model that will predict `median_house_value`.
- Create an API that compute a prediction.
- Find a way to dockerize the model inference API using the image name `housing-model`.
