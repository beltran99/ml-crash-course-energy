# Machine Learning and Data Science in Energy
This repository aims to provide basic insights in Machine Learning and Data Science for Electrical Engineering students in the shape of a data-centered practical example.
The jupyter notebook [Electricity Price Forecasting](notebooks/electricity_price_forecasting.ipynb) presents a time-series forecasting case based on this [Kaggle dataset](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather), which contains 4 years of electrical consumption, generation, pricing, and weather data for Spain.
We will focus on the consumption and generation data to perform some electricity price forecasting, making emphasis on data pre-processing and feature engineering techniques.

# Installation
1. Create a Kaggle account: https://www.kaggle.com/
2. Clone the repository
```bash
git clone https://github.com/beltran99/ml-crash-course-energy
```
3. (Recommended) You can use your favourite virtual environment manager (venv / virtualenv / poetry / anaconda / etc...) to create a new environment with all the required packages for this repository.
```bash
# conda
conda create --name <env_name> --file conda_requirements.txt
```
```bash
# virtualenv
virtualenv <env_name>
source <env_name>/bin/activate
pip install -r requirements.txt
```

**NOTE:** if you use Jupyter and Anaconda, remember to activate your *base* environment and launch a jupyter notebook. Then, the web interface should allow you to select the specific virutal environment you created for this project.