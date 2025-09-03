# Data Analysis with Python & Panda

   This project focused on analyzing a dataset containing information about data scientist roles and salaries. 
   The primary objective was to extract meaningful insights through data cleaning, exploration, and visualization.

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

# 📈 Data Exploration / Visualization Stage
Generated statistical visualizations including:
- Histograms to observe distribution patterns
- Boxplots to detect outliers and understand data spread
- Bar charts to compare categorical variables

## 🛠️🔧 Tools & Technologies
- Language: Python
- Libraries Used: Pandas for data manipulation, Matplotlib for visualizations
- Development Environment: Visual Studio Code with a virtual environment (venv)
- Dashboard Framework: Streamlit

## ⚙️ Setup and Installation

      - Create the virtual environment: python3 -m venv .venv
      - Activate the virtual environment on Windows: .venv\Scripts\Activate
      - Activate the virtual environment on MAC/LINUX: source .venv/bin/activate
      - Create a file called requirements.txt and add the necessary packages. pandas==2.2.3 streamlit==1.44.1 plotly==5.24.1
      - Install the necessary libraries. pip install -r requirements.txt
      - Create the Dashboard Interface with Streamlit
      
## 🌐 Dashboard Deployment
Built an interactive dashboard using Streamlit to allow users to:

 - Filter data dynamically
 - Generate custom visualizations

Successfully deployed the dashboard to Streamlit Cloud, making it accessible online: https://aplication-data-science.streamlit.app/ 



