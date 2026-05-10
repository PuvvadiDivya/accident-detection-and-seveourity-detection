# accident-detection-and-seveourity-detection
Accident Detection and Severity Prediction Using Machine Learning

An intelligent Machine Learning project that predicts the severity of road traffic accidents using real-world accident datasets. 
This system analyzes accident-related factors such as weather conditions, road surface conditions, vehicle type, and light conditions to classify accidents into categories like Slight Injury, Serious Injury,
and Fatal Injury.

The project also integrates a Telegram Bot for real-time user interaction and prediction.

📌 Features
Accident severity prediction using Machine Learning

Multiple ML algorithms implemented:
Random Forest Classifier
Support Vector Machine (SVM)
Neural Network (MLP Classifier)
Data preprocessing and feature engineering
Visualization of accident patterns
Telegram Bot integration for real-time predictions
Uses real-world Road Traffic Accident dataset

🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Telegram Bot API
Asyncio

📂 Dataset
The project uses the RTA Dataset (Road Traffic Accident Dataset) collected from real-world accident records.

Important Features Used:
Weather Conditions
Road Surface Conditions
Type of Vehicle
Light Conditions
Accident Severity

Dataset source: Kaggle (Ethiopian Road Traffic Accident Dataset).

⚙️ Machine Learning Workflow
Data Collection
Data Preprocessing
Feature Selection
Train-Test Split
Model Training
Model Evaluation
Prediction
Telegram Bot Integration

🤖 Algorithms Used
1. Random Forest Classifier
Ensemble learning algorithm
Good accuracy for classification problems
Handles categorical and numerical data efficiently

2. Support Vector Machine (SVM)
Uses RBF kernel
Effective for non-linear classification
Performs well in high-dimensional spaces

3. Multi-Layer Perceptron (MLP)
Neural network-based classifier
Learns complex non-linear relationships
📊 Visualizations

The project includes:

Accident Severity Distribution
Weather Conditions vs Severity
Road Surface vs Severity
Light Conditions vs Severity
Vehicle Type vs Severity

📁 Project Structure:

Accident-Severity-Prediction/
│
├── dataset/
│   └── RTA Dataset.csv
│
├── notebook/
│   └── accident_prediction.ipynb
│
├── bot/
│   └── telegram_bot.py
│
├── images/
│   └── output_screenshots.png
│
├── requirements.txt
└── README.md

🚀 Installation
1. Clone the Repository
git clone https://github.com/your-username/Accident-Severity-Prediction.git

2. Navigate to Project Folder
cd Accident-Severity-Prediction

3. Install Required Libraries
pip install -r requirements.txt

▶️ Run the Project
Run Machine Learning Model
python main.py
Run Telegram Bot
python telegram_bot.py

📈 Model Performance
Model	Accuracy
Random Forest	83.6%
SVM	83.7%


⚠️ Limitations
Accuracy depends on dataset quality
Requires continuous updates
Class imbalance affects predictions
Internet required for Telegram Bot

📌 Future Enhancements
Integration with IoT sensors
Real-time CCTV accident detection
Deep Learning implementation
Mobile application support
Cloud deployment

👩‍💻 Authors
P. Divya
G. Ramya
K. Satyasri
P. Jahnavi

Under the guidance of D. Harshini
PACE Institute of Technology & Sciences

📜 Conclusion

This project demonstrates how Machine Learning can be effectively used in road safety systems for accident detection and severity prediction.
By integrating predictive analytics with real-time communication through a Telegram Bot, the system can support faster emergency responses and improve traffic management strategies.
