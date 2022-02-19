This exploratoy data analysis requests data from openFDA API and investigates datasets for any medical device trends or insights. Data visualizations are used to better display the findings and reveal key statistics on FDA medical devices.

*****FOR INTERACTIVE DATA VISUALIZATIONS, follow steps:
1. Click the following link: https://colab.research.google.com/drive/1RV9fvednj_5eJfit4Sde4sxBw-OUBiqY?usp=sharing
2. Select blue "Open in Colab" button located above script
3. Sign into Google account
4. On the top tool bar, select "Runtime" --> "Run all"'
5. Each section will then display a dataframe and visualization


Skills involved in this EDA:
- Data collection via API
- Data cleaning/preparation
- Exploratory data analysis and data visualizations

Process:
1. Use python requests library to make API call to openFDA API
2. Construct url per openFDA API query syntax rules and passed url to API to retrieve specific data desired
3. Collected data as JSON object
4. Parsed through data and saved data into pandas dataframe
5. Created static and interactive visualizations using Plotly and Matplotlib
