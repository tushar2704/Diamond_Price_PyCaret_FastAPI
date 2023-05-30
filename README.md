# Diamond_Price_PyCaret_FastAPI
Welcome to the Diamond Price Prediction project repository! This project utilizes the power of PyCaret and FastAPI to build a robust machine learning model that predicts the price of diamonds based on their characteristics. Whether you're a data enthusiast, a machine learning practitioner, or simply curious about diamond prices, this repository is designed to help you understand the process of building a predictive model and deploying it as a web API.

## Introduction
The Diamond Price Prediction project aims to leverage machine learning techniques to predict the price of diamonds using a dataset that includes various attributes such as carat weight, cut, color, clarity, and depth. PyCaret, a Python library for automated machine learning, is used to streamline the end-to-end machine learning workflow. FastAPI, a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints, is employed to develop the API for the diamond price prediction model.

## Features
* ### Machine Learning Model:
 The project utilizes PyCaret, which provides an automated machine learning workflow, to build a diamond price prediction model. PyCaret takes care of data preprocessing, feature engineering, model selection, hyperparameter tuning, and model evaluation, making it easy for both beginners and experienced practitioners to build high-quality models.
* ### API Development:
 FastAPI is used to develop a web API that exposes the trained machine learning model. This allows users to make HTTP requests to the API and obtain predictions for diamond prices based on their characteristics.
* ### Docker Support: 
 The project includes Docker support, allowing you to containerize the application and deploy it easily in different environments without worrying about dependencies and configurations.
* ### Documentation: 
 Detailed documentation is provided, guiding you through the steps to train the model, deploy the API, and interact with it using various HTTP requests.
## Getting Started
To get started with the Diamond Price Prediction project, follow these steps:
1. Clone the repository to your local machine using the following command:
```
git clone https://github.com/tushar2704/Diamond_Price_PyCaret_FastAPI.git
```
2. Install the required dependencies by running:
```
pip install -r requirements.txt
```
3. Preprocess the data and train the machine learning model by executing the Jupyter notebook diamond_price_prediction.ipynb. This notebook guides you through the steps of data preprocessing, model training, and evaluation using PyCaret.
4. Once the model is trained, you can start the FastAPI server by running the following command:
```
uvicorn main:app --reload
```
5. The API will be accessible at http://localhost:8000. Refer to the documentation for more information on the available endpoints and how to make predictions using different HTTP requests.
6. Interact with the API using your preferred HTTP client (e.g., cURL, Postman) to make predictions for diamond prices based on their characteristics.
7. Feel free to experiment with the code, make improvements, and customize the project to fit your needs. Contributions are always welcome!

## Roadmap
The Diamond Price Prediction project has an exciting roadmap ahead:
* Enhancing the machine learning model by incorporating advanced techniques and algorithms.
* Adding more features to the API, such as batch prediction support and additional endpoints for data exploration.
* Optimizing the performance and scalability of the API to handle high request volumes.
* Developing a user-friendly web interface to enable users to interact with the model without requiring HTTP clients.
* Stay tuned for updates as the project evolves!

## Support
If you encounter any issues, have questions, or would like to discuss the project, please feel free to open an issue in the repository. I am here to help!
## Author
- <ins><b>©2023 Tushar Aggarwal. All rights reserved</b></ins>
- <b>[LinkedIn](https://www.linkedin.com/in/tusharaggarwalinseec/)</b>
- <b>[Medium](https://medium.com/@tushar_aggarwal)</b> 
- <b>[Tushar-Aggarwal.com](https://www.tushar-aggarwal.com/)</b>
- <b>[Kaggle](https://www.kaggle.com/tusharaggarwal27)</b> 

## License
The Diamond Price Prediction project is licensed under the <ins>MIT License.</ins>

### Start predicting diamond prices with the power of machine learning and fast API development using Diamond Price Prediction with PyCaret and FastAPI!
