# AUTOMATIC-TOLL-SYSTEM-AND-VEHICLE-IDENTIFICATION-ALONG-WITH-CAR-BRANDS-USING-CV
📌 Overview

This project automates toll booth operations by eliminating manual intervention. It uses:

📷 Image processing to detect vehicles
🔍 OCR to extract vehicle numbers
🤖 Deep Learning to classify vehicle type & brand
💰 Machine Learning to calculate toll fees

The system generates a complete digital toll receipt including entry time, exit time, vehicle details, and fee.

🚀 Features
🧹 Dataset Cleaning
Removes unsupported file formats
Detects and deletes corrupted images
🧠 Deep Learning Models
Vehicle Type Classification (Car, Truck, Auto, etc.)
Vehicle Brand Detection (for cars)
Built using MobileNetV2 (Transfer Learning)
🔍 OCR (Number Plate Detection)
Uses Tesseract OCR
Extracts vehicle registration number from image
💰 Toll Fee Prediction
Uses Linear Regression Model
Calculates toll based on:
Vehicle type
Distance traveled
🧾 Automated Receipt Generation
Vehicle number
Entry & exit time
Vehicle type & brand
Distance traveled
Toll fee
🛠️ Tech Stack
Category	Technology
Programming	Python
Deep Learning	TensorFlow / Keras
Pretrained Model	MobileNetV2
Image Processing	OpenCV, PIL
OCR	Tesseract
ML Model	Scikit-learn (Linear Regression)
Data Handling	Pandas, NumPy
🧠 System Workflow
Clean dataset (remove invalid/corrupted images)
Load and preprocess images
Train:
Vehicle Type Model
Vehicle Brand Model
Train toll prediction model
Upload vehicle image
Extract number plate using OCR
Predict:
Vehicle Type
📥 Input
Vehicle image (uploaded by user)
📤 Output (Sample Receipt)
----------------------TOLL RECEIPT----------------------

Vehicle Number : KA01AB1234
Entry Time     : 2026-03-31 17:20:13
Vehicle Type   : Car
Car Brand      : Honda City
Distance       : 48 km
Toll Fee       : ₹137.0
Exit Time      : 2026-03-31 17:45:10

---------------------------END---------------------------
🤖 Models Used
📌 1. Vehicle Type Model
MobileNetV2 (Transfer Learning)
Output: Type of vehicle
📌 2. Brand Detection Model
MobileNetV2
Activated only for cars
📌 3. Toll Prediction Model
Linear Regression
Inputs:
Encoded vehicle type
Distance
📊 Key Highlights
Fully automated toll system
Combines CV + OCR + ML
Real-time prediction & billing
Scalable for smart city applications
💡 Future Enhancements
Real-time camera integration (CCTV)
License plate detection using YOLO
Database storage of transactions
Web dashboard (Flask integration)
Multi-lane toll system support
⚠️ Limitations
OCR accuracy depends on image quality
Limited dataset affects prediction accuracy
Distance is randomly generated (can be improved using GPS)
👩‍💻 Author

Sahana R

📜 License

This project is open-source under the MIT License.
Vehicle Brand
Calculate toll fee
Generate receipt
