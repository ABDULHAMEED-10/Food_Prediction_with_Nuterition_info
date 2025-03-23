# Food Recognition and Nutritional Information System

This project is a **Food Recognition and Nutritional Information System** that uses a pre-trained ResNet-50 model to classify food images into one of 101 food categories. Once the food is recognized, the system fetches its nutritional information using the USDA FoodData Central API.

---

## Features
1. **Food Recognition**:
   - Classifies food images into 101 categories using a pre-trained ResNet-50 model.
   - Displays the top 5 predictions with confidence scores.

2. **Nutritional Information**:
   - Fetches nutritional details (calories, protein, carbs, fats) using the USDA FoodData Central API.

3. **Easy to Use**:
   - Upload an image, and the system will predict the food and display its nutritional information.

---

## Prerequisites
Before running the code, ensure you have the following:
1. **Python 3.8+** installed.
2. **Google Colab** or a local Python environment.
3. **API Key** from [USDA FoodData Central](https://fdc.nal.usda.gov/api-key-signup).

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Abdulhameed-10/Food_Prediction_with_Nuterition_info.git
   cd food-recognition-system

2. Install the required Python libraries:
   
   ```bash
   pip install torch torchvision Pillow requests
  
3. Download the pre-trained ResNet-50 model:

   Download the model from this [link](https://drive.google.com/file/d/1uEVf48Bj1fnwPlfSx31hE9SP3g4_RjuA/view).

4. Place the model file (resnet50model.pth) in the root directory of the project.
