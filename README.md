# Superstore EDA with Streamlit
The project "**Superstore EDA with Streamlit**" involves building a web application using Streamlit to perform Exploratory Data Analysis (EDA) on a dataset from a fictional superstore. 
Exploratory Data Analysis is the process of analyzing and visualizing data sets to extract insights and discover patterns, trends, and anomalies.

### Project Overview:

1. *Data Loading*: The project starts by loading the dataset containing information about sales transactions in the superstore. This dataset typically includes details such as order date, product category, sub-category, sales, quantity, and customer segment.

2. *Data Exploration*: Once the data is loaded, the application displays the dataset's basic information, such as the first few rows, summary statistics, and other relevant statistics like mean, median, and standard deviation.

3. *Interactive Visualization*: The application provides interactive visualizations to explore the dataset further. Users can choose different categories or sub-categories and visualize sales data using bar charts, line charts, and other plots. These interactive plots allow users to gain insights into sales trends, patterns, and correlations.

4. *Correlation Analysis*: The application includes a scatterplot visualization of the correlation matrix to identify relationships between different numerical variables. This helps users understand how sales are correlated with other factors such as profit, discount, and quantity.

5. *Time Series Analysis*: The application includes a time series analysis section where users can visualize sales trends over time. This section typically includes line charts or area plots showing sales trends aggregated by date or time period.

6. *Data Filtering*: The application provides options for users to filter the dataset based on specific criteria such as product category or sub-category. This allows users to focus on analyzing specific segments of the data.

7. *Deployment*: Once the application is developed, it can be deployed on a web server or cloud platform to make it accessible to users. Streamlit provides built-in functionality for deploying applications, making it easy to share with others.

### Requirements

### Libraries:

1. streamlit==1.35.0
2. pandas==2.2.2
3. numpy==1.26.4
4. matplotlib==3.9.0
5. seaborn==0.13.2
6. plotly==5.22.0
7. scikit-learn==1.5.0

### Here's a brief explanation of the included libraries:

1. *streamlit*: Streamlit is the primary framework used to develop the web application. It allows developers to create interactive web applications using simple Python scripts.
2. *pandas*: Pandas is used for data manipulation and analysis. It is particularly useful for loading, exploring, and filtering tabular data.
3. *numpy*: NumPy is used for numerical computing and array operations. It provides efficient data structures and functions for handling numerical data.
4. *matplotlib*: A plotting library for creating static, animated, and interactive visualizations.
5. *seaborn*: A Python visualization library based on matplotlib that provides a high-level interface for drawing attractive statistical graphics.
6. *plotly*: Used for creating interactive plots. It allows users to interact with the data by zooming, panning, and hovering over data points.
7. *scikit-learn*: Scikit-learn is used for machine learning tasks such as clustering, classification, and regression. While not explicitly used in this project, it can be integrated for more advanced analysis if needed.

### Deploy the Streamlit app:

Make sure you have Streamlit installed in your local environment.
Run the app locally to test:

- streamlit run your_app.py

### Project Benefits:

- Provides a user-friendly interface for exploring and analyzing sales data from the superstore.
- Allows users to gain insights into sales trends, patterns, and correlations.
- Facilitates data-driven decision-making by providing interactive visualizations and tools for exploring the dataset.
- Enhances collaboration and knowledge sharing by making the analysis accessible to a wider audience.
