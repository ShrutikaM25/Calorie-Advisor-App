# Calorie Advisor Website

Welcome to the Calorie Advisor website! This web application utilizes state-of-the-art technologies including Streamlit, LIM (Language Image Model), and Google's Generative AI (Gemini-Pro-Vision) to provide comprehensive information about food items displayed in images. 

## Features

- **Image Input**: Users can upload images in JPG, JPEG, or PNG format.
- **Dish Recognition**: The application identifies the dish being displayed in the image.
- **Calorie Information**: Provides the calorie count for each item in the image and calculates the total calorie count for the dish.
- **Nutritional Information**: Displays additional information about the food items, such as macronutrient composition and key nutrients.
- **Health Advice**: Offers advice on whether the identified dish is healthy or not.

## Technologies Used

- **Streamlit**: A Python library for building interactive web applications.
- **LIM Model (Language Image Model)**: A model trained to understand the context of images and their corresponding text.
- **Google Generative AI (Gemini-Pro-Vision)**: State-of-the-art AI model for image recognition and analysis.

## Usage

1. Upload an image containing the food item you want to analyze.
2. The application will process the image and identify the dish.
3. It will provide information about the calorie count, nutritional details, and health advice for the identified dish.
4. Users can make informed decisions about their dietary choices based on the provided information.

## Supported Image Formats

- JPG
- JPEG
- PNG

## Installation

To run the application locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/your/repository.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

4. Access the application in your web browser at `http://localhost:8501`.

