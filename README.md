## Vehicle Emissions Analysis and Prediction

This project aims to analyze the relationship between vehicle characteristics and CO2 emissions, providing insights into the environmental impact of different vehicle types. It includes a data analysis component using machine learning models and a Streamlit web application that leverages YOLOv8n for real-time object detection in traffic videos.

##### Link: https://vehicle-emissions-analysis-using-yolov8.onrender.com/

### Project Overview

The transportation sector significantly contributes to greenhouse gas emissions, and vehicle size plays a crucial role. This project quantifies this impact by:

1. Analyzing a dataset of vehicle specifications and CO2 emissions to identify key relationships.
2. Building machine learning models to predict a vehicle's CO2 emissions based on its attributes.
3. Developing a Streamlit application that uses YOLOv8n to detect vehicles in videos, estimate their CO2 emissions, and provide users with actionable insights.

Key Features

* Data Analysis:
    * Dataset cleaning and exploration (EDA) to understand patterns in vehicle data.
    * Feature engineering to enhance predictive modeling.
    * Training and evaluation of multiple machine learning models, including Ridge Regression (best performer).
* YOLOv8n Object Detection:
    * Training a YOLOv8n model on annotated traffic videos to accurately detect cars, trucks, and buses.
* Streamlit Application:
    * User-friendly interface for uploading videos.
    * Real-time vehicle detection and classification using the trained YOLOv8n model.
    * Estimation of total CO2 emissions based on detected vehicle types.
    * Interactive visualization of results.

# Key Findings

* Heavy vehicles (e.g., trucks, buses) are the largest contributors to CO2 emissions, with an average of 284.30 g/km.
* Smaller vehicles (e.g., compact cars) significantly reduce emissions, with an average of 181.74 g/km for the lowest category.
* Machine learning models, especially Ridge Regression, accurately predict CO2 emissions based on vehicle attributes.

### Getting Started
1. **Create Environment:**
   ```bash
   conda create -n <environment name> python=3.8 -y
   ```

2. **activate environment:**
   ```bash
   conda activate <environment name>
   ```
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/kundan-raj301/-vehicle-emissions-analysis-using-yolov8.git
   ```
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Streamlit App:**
   ```bash
   streamlit run app.py
   ```
4. **Upload a Video:** Use the app to upload a traffic video and get insights into the vehicle types and their estimated CO2 emissions.

### Future Scope

* Real-time emissions monitoring integration with traffic systems.
* Development of data-driven recommendations for policymakers.
* Public awareness and education campaigns.
* Expansion of YOLOv8n's vehicle detection capabilities.
* Integration with additional data sources (e.g., traffic patterns, weather).

### Project Output :

![image](https://github.com/kundan-raj301/-vehicle-emissions-analysis-using-yolov8/assets/126227974/c2d6c739-0295-482f-89fb-4a8a54267f5c)


### Acknowledgments

Special thanks to my supervision  ** Dharmendra Singh** for their invaluable guidance and support throughout this project.
