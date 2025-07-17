## 🧠 ML Pipeline with DVC & MLflow: RandomForest Model for Diabetes Prediction
This project demonstrates a robust, reproducible end-to-end machine learning pipeline for classifying diabetes using the Pima Indians Diabetes Dataset. It leverages:

📦 DVC for data and model versioning
📊 MLflow for experiment tracking
🌲 Random Forest Classifier for modeling
☁️ DagsHub (with AWS S3) for remote cloud storage!

# 🚀 Key Features
✅ Data Version Control (DVC):
Track datasets, models, and pipeline stages with reproducibility.
Automatically re-run pipeline steps when dependencies change.
Uses DagsHub's built-in AWS S3-backed remote for secure, versioned data storage.
📈 Experiment Tracking (MLflow):
Log hyperparameters, accuracy metrics, and models.
Visualize and compare experiment runs easily.

# 🛠️ Tools & Technologies Used
Category	Tool/Technology
👨‍💻 Programming	Python
🔍 Model	Scikit-learn (Random Forest)
📦 Data Versioning	DVC
📊 Experiment Tracking	MLflow
☁️ Remote Storage	DagsHub (backed by AWS S3)

# 🧬 Project Structure
ML_pipeline_RandomForest_Diabetes_dataset/ ├── data/ │ ├── raw/ │ └── processed/ ├── models/ │ └── model.pkl ├── src/ │ ├── preprocess.py │ ├── train.py │ └── evaluate.py ├── dvc.yaml ├── dvc.lock ├── params.yaml ├── README.md └── dagshub.txt
