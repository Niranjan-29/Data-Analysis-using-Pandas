# 🚗 Traffic Crashes Analysis

This project performs an in-depth analysis of traffic crash data to identify patterns, contributing factors, and key trends. By leveraging Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**, this analysis provides valuable insights into when, where, and why traffic accidents occur.



***

## 📋 Table of Contents

* [Project Objective](#-project-objective)
* [Dataset](#-dataset)
* [Key Questions](#-key-questions-answered)
* [Tools & Libraries](#-tools--libraries)
* [Analysis Highlights](#-analysis-highlights)
* [How to Run](#-how-to-run)
* [Author](#️-author)

***

## 🎯 Project Objective

The primary goal of this project is to analyze a comprehensive dataset of traffic crashes to:
* Identify temporal patterns (e.g., crashes by year, month, day of the week).
* Determine the impact of environmental factors like weather and lighting conditions.
* Uncover the primary causes of accidents.
* Visualize the data to make the findings easily understandable.

***

## 🗃️ Dataset

The analysis is based on the `Traffic_Crashes.csv` dataset, which contains detailed records of traffic incidents. Each record includes a wide range of attributes, such as:
* `CRASH_DATE`: The date and time of the crash.
* `WEATHER_CONDITION`: Weather conditions at the time of the incident.
* `LIGHTING_CONDITION`: Lighting conditions (e.g., daylight, darkness).
* `FIRST_CRASH_TYPE`: The nature of the initial impact.
* `PRIM_CONTRIBUTORY_CAUSE`: The main reason for the crash.
* `INJURIES_TOTAL`: The total number of injuries.
* `LOCATION`: Geographic coordinates of the crash.

***

## ❓ Key Questions Answered

This analysis seeks to answer several critical questions, including:
1.  How has the number of crashes changed over the years?
2.  What are the most common weather conditions during a crash?
3.  Which day of the week has the highest frequency of accidents?
4.  What are the leading causes of traffic crashes?
5.  Is there a correlation between lighting conditions and the severity of injuries?

***

## 🛠️ Tools & Libraries

This project is developed using Python within a notebook environment and relies on the following core data science libraries:
* **Google Colab / Jupyter Notebook:** As the interactive environment for developing and executing the analysis.
* **Pandas:** For data manipulation, cleaning, and aggregation.
* **Matplotlib:** For creating static, high-quality visualizations.
* **Seaborn:** For generating more attractive and informative statistical graphics.

***

## 📊 Analysis Highlights

* **Crashes by Year:** The analysis reveals a clear trend in the number of crashes over time, with a notable bar chart visualizing the year-over-year data.
* **Weather Impact:** A stacked bar chart effectively shows the distribution of crashes under different weather conditions for each year, highlighting that most accidents occur in clear weather, but also showing significant numbers during rain and snow.
* **Data Cleaning:** Unnecessary columns like `CRASH_RECORD_ID` were dropped to streamline the dataset for analysis.



***

## 🚀 How to Run

You can run this analysis in either Google Colab or a local Jupyter Notebook environment.

### In Google Colab (Recommended)
1.  Upload the `Traffic_Crashes_Analysis.ipynb` file to your Google Drive.
2.  Open the notebook with Google Colaboratory.
3.  In the Colab file browser (folder icon on the left), upload the `Traffic_Crashes.csv` dataset to the session storage.
4.  Run the cells sequentially to execute the analysis. The notebook will read the CSV file directly from the session storage.

### In a Local Jupyter Notebook
1.  Ensure you have Python and Jupyter Notebook installed on your machine.
2.  Install the required libraries by running the following command in your terminal:
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  Place both the `Traffic_Crashes_Analysis.ipynb` file and the `Traffic_Crashes.csv` dataset in the same project directory.
4.  Launch Jupyter Notebook from your terminal:
    ```bash
    jupyter notebook
    ```
5.  Open the `.ipynb` file and run the cells sequentially.

***

## ✍️ Author

* Created by: **Niranjan S**
