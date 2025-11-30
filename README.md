Greetings Traveler,  


Let’s begin our coding quest! Below is the complete `README.md` file for the "Intelligent Crop Recommendation Portal" repository.

* * *

# Intelligent Crop Recommendation Portal 🌾

This repository hosts the Intelligent Crop Recommendation Portal, a machine learning-powered web application designed to assist farmers and agricultural specialists in selecting the best crops and fertilizers based on soil characteristics and environmental parameters. Developed by Dev Raj, this project leverages nutrient data and predictive models to make insightful agricultural recommendations.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Directory Structure](#directory-structure)
- [Installation](#installation)
- [Usage](#usage)


---

## About the Project

The Intelligent Crop Recommendation Portal is a web-based recommendation system aimed at improving crop yield and fertilizer application by utilizing machine learning models. By analyzing soil nutrient levels and environmental factors, the portal provides recommendations on the most suitable crops, as well as optimal fertilizers and pesticides, fostering sustainable agricultural practices.

---

## Features

- **Crop Recommendation:** Suggests the best crops based on soil nutrient content and environmental data.
- **Fertilizer Recommendation:** Provides fertilizer suggestions tailored to crop types and soil characteristics.
- **Pesticide Guidance:** Recommends pesticides for managing common pests.
- **Data Visualization:** Offers visual insights on soil nutrients and crop recommendations.
- **User-Friendly Web Application:** Interactive interface for easy access to recommendations and information.

---

## Directory Structure

### Data Directory
- **Crop_NPK.csv** and **crop_recommendation.csv**: Contain nutrient values and recommendations for different crops.

### Models
- **cnn_model.ipynb** and **crop_model.ipynb**: Jupyter notebooks for training and evaluating models.
- **Trained_Model_1.h5**: Saved model file used for crop and fertilizer recommendations.

### Application Files
- **app.py**: Main application file, likely a Flask app for running the web server.
- **requirements.txt** and **runtime.txt**: Specify Python dependencies and runtime requirements.

### Frontend
- **Static**: Contains CSS, JavaScript, and image resources for the web application's front end.
- **Templates**: HTML templates such as `CropRecommendation.html` and `FertilizerRecommendation.html` for rendering the crop and fertilizer recommendation views.

### Utils Directory
- **fertilizer.py**: Contains utility functions for suggesting fertilizers based on crop nutrient requirements.

---

## Installation

Follow these steps to set up and run the application locally.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/devraj-io/AI-Crop-Prediction.git
    ```

2.  **Install Dependencies:**  
    Ensure Python is installed, then run:
    
    ```bash
    pip install -r requirements.txt
    ```
    
3.  **Run the Application:**
    
    ```bash
    python app.py
    ```
    
    The app will start on `localhost:5000` by default.
    

* * *

Usage
-----

1.  **Crop Recommendation:**
    
    *   Navigate to the Crop Recommendation page.
    *   Input soil parameters (NPK values, moisture, temperature, etc.).
    *   Receive a list of recommended crops based on the provided data.
2.  **Fertilizer Advice:**
    
    *   Use the Fertilizer Recommendation section.
    *   Input the crop type and soil nutrient needs to get tailored fertilizer suggestions.
3.  **Pesticide Information:**
    
    *   Access information on pest management strategies.
    *   Find suitable pesticides for common pests based on crop types and region.


* * *

Enjoy farming smarter! 🌱✨

* * *



