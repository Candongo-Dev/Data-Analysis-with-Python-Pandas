# Data Analysis with Python & Panda

This project aimed to analyze a dataset detailing data scientist salaries and roles. 
Using Python with the Pandas library, we performed data cleaning to ensure accurate analysis. 
We explored the dataset through statistical visualizations histograms, boxplots, and bar charts created with Matplotlib.

To enhance accessibility, we built an interactive dashboard using Streamlit, enabling users to filter data and generate graphs efficiently. 
Development was carried out in Visual Studio Code within a Python virtual environment (created via venv). 
The final dashboard was successfully deployed to Streamlit Cloud.

# 📊 Data 
The primary dataset used in this application is a cleaned CSV file derived from the Alura Archive.

- File: Data ("https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv")
- Access Date: 2025

# 🔬 How It Works
## In (Data_Analysis_with_Python_&_Pandas.ipynb) you can find all detailed analysis:

1. Renaming DataFrame Columns
2. Analyzing what the categories of categorical columns are
   - Contract Type & Contract Type Description
   - Work regime
   - Company size
3. Changing category names:
   - 'SE': Senior
   - 'MI': Mid-level
   - 'EN': Entry-level
   - 'EX': Executive

# 🚀Data preparation and cleaning
The code serves as a step-by-step guide for understanding, cleaning, and preparing the dataset for more in-depth analysis, enabling clearer visualization of patterns and trends within the data science job market.

With this initial analysis, we were able to answer several key questions, such as:
- What is the most common level of experience in the dataset?
- What is the predominant type of contract?
- Which job position appears most frequently in the sample?
- Which country do most professionals in the dataset come from?
- Where are the majority of companies in the sample headquartered?
- What is the most common employment status?
- What is the typical size of companies represented in the sample?

# 📊📊 Data Visualization Stage
Statistical graphs are essential for exploring and conveying insights from data. I used histograms, boxplots, and bar charts to enhance the understanding and interpretation of the DataFrame.

## 🛠️  Technical Stack
- Language: Python
- Code editor used: Jupyter Notebook - Google Colab (in the cloud)
- Web Framework: Streamlit
- Data Manipulation: Pandas, NumPy
- Data Visualization: Plotly, Matplotlib

## ⚙️ Setup and Installation

Build an interactive dashboard with Streamlit to filter data and create practical visualizations.

- Create the virtual environment: python3 -m venv .venv
- Activate the virtual environment on Windows: .venv\Scripts\Activate
- Activate the virtual environment on MAC/LINUX: source .venv/bin/activate
- Create a file called requirements.txt and add the necessary packages. pandas==2.2.3 streamlit==1.44.1 plotly==5.24.1
- Install the necessary libraries. pip install -r requirements.txt
- Create the Dashboard Interface with Streamlit
- We did the deploy the Dashboard to Streamlit Cloud: https://streamlit.io/cloud
