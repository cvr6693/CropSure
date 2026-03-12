## 🌱 CropSure – Smart Crop, Fertilizer Recommendation & Plant Disease Detection System
CropSure is a Machine Learning–based web application designed to support farmers and agricultural researchers in making better farming decisions. The system predicts the most suitable crop to grow, recommends the appropriate fertilizer, and detects plant diseases from leaf images.
The application integrates Machine Learning and Deep Learning models with a web interface built using Flask.
 
## 🚀 Features
🌾 Crop Recommendation
Predicts the most suitable crop based on soil and environmental conditions such as:

•	Nitrogen (N)

•	Phosphorus (P)

•	Potassium (K)

•	Temperature

•	Humidity

•	Soil pH

•	Rainfall

🌿 Fertilizer Recommendation
Suggests the most appropriate fertilizer based on:

•	Crop type

•	Soil nutrient values

•	Environmental factors

🍃 Plant Disease Detection
Detects plant diseases from leaf images using a deep learning model based on ResNet architecture.
 
## 🧠 Machine Learning Models Used

Crop Recommendation	Random Forest

Fertilizer Recommendation	Random Forest

Plant Disease Detection	ResNet 

Random Forest models are used for crop and fertilizer prediction because they perform well with structured agricultural datasets, while ResNet is used for image-based disease detection.
 
## 🛠 Technologies Used
•	Python

•	Flask

•	Scikit-learn

•	TensorFlow / Keras

•	Pandas

•	NumPy

•	HTML

•	CSS

•	JavaScript

•	OpenCV
 
## ⚙️ Installation
Clone the repository

git clone https://github.com/LaharikaReddy6693/Cropsure.git

Navigate to the project folder

cd Cropsure

Install required dependencies

pip install -r requirements.txt
 
▶️ Running the Application

Run the Flask application:
python app.py
 
## 📸 Project Screenshots
Home Page
  
 ![home](https://github.com/user-attachments/assets/2cc380cd-72d2-4ee2-96d6-f0d78e61e2f2)

 ![Next](https://github.com/user-attachments/assets/1c9ea367-fabd-4b72-ab4a-07e2606c6bbe)


Crop Recommendation
![crop recommendation](https://github.com/user-attachments/assets/aee852d2-fcbf-46e8-a578-c1537294627e)

![crop recommendation result](https://github.com/user-attachments/assets/03ebb2fd-a544-4880-bd27-19a28e45bef5)

 
 
Fertilizer Recommendation
![fertilizer suggestion](https://github.com/user-attachments/assets/2a5a1388-7925-4037-bb19-a968b0fed5f9)

  ![IMG_1126](https://github.com/user-attachments/assets/413ff184-1319-4fae-8dcc-ebc25a3b2f62)

 
Plant Disease Detection
  ![plant disease detection](https://github.com/user-attachments/assets/8b230186-dcc0-4c78-a500-6b3259a58888)

 
## 🏗 System Architecture

![IMG_1127](https://github.com/user-attachments/assets/5041776a-8b75-44e7-8eb9-fdc6030ba86f)

 
 

## 📊 Model Performance

The machine learning models used in CropSure were evaluated using agricultural datasets to ensure reliable predictions.

| Module | Model Used | Description |
|------|------|------|
| Crop Recommendation | Random Forest | Predicts the most suitable crop based on soil nutrients and environmental factors |
| Fertilizer Recommendation | Random Forest | Suggests appropriate fertilizers depending on soil nutrient levels |
| Plant Disease Detection | ResNet  | Identifies plant diseases from leaf images using deep learning |

 

## ⚠️ Important Notes
Due to GitHub file size limitations:

•	The Plant Disease Detection model (plant_disease_resnet_finetuned.h5) is not included in this repository.

•	The plant disease dataset is also not uploaded because it is too large.

However, the training notebook is provided, so the model can be reproduced using:
notebooks/plant_disease_training.ipynb
 
## 🌍 Applications
This system can help:
•	Farmers choose the best crop for their soil

•	Improve agricultural productivity

•	Detect plant diseases early

•	Reduce crop losses

•	Support precision farming

 
## 🔮 Future Improvements
Possible enhancements include:

•	Deploy the application on cloud platforms

•	Integrate real-time weather APIs

•	Add more crop and fertilizer datasets

•	Improve disease detection accuracy

•	Develop a mobile-friendly interface

 
## Acknowledgement
This project was inspired by the Harvestify open-source agriculture recommendation system: https://github.com/Gladiator07/Harvestify
 
## 👩‍💻 Author
Laharika Reddy

Computer Science Graduate
Interested in Machine Learning, Cloud Computing, and Software Development.
GitHub https://github.com/LaharikaReddy6693
 
## 📜 License
This project is licensed under the MIT License.


