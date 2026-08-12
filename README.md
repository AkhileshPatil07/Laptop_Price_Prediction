# 💻 Laptop Price Prediction

A machine learning project that predicts the **price of a laptop** based on its specifications and features. The project follows a modular and structured machine learning architecture, making the workflow easier to maintain, test, and deploy.

The project includes separate components for data processing, model training, prediction, configuration, logging, exception handling, and application deployment.

---

## 🚀 Project Overview

Laptop prices vary depending on specifications such as processor, RAM, storage, graphics card, display, operating system, and other hardware features.

The objective of this project is to build a machine learning system that learns from historical laptop data and predicts the expected price of a laptop based on its specifications.

The project is designed using a **modular ML pipeline architecture**, separating different stages of the machine learning workflow.

### 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Ingestion
   ↓
Data Transformation
   ↓
Feature Engineering
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Artifact
   ↓
Prediction
   ↓
Web Application
```

---

## ✨ Key Features

* 📊 Laptop price prediction using Machine Learning
* 🔄 Modular machine learning pipeline
* 🧹 Data preprocessing and transformation
* ⚙️ Configurable project architecture
* 🤖 Model training and prediction pipeline
* 📦 Model artifact management
* 📝 Logging system for tracking application execution
* ⚠️ Custom exception handling
* 🔍 Model checking utility
* 🌐 Application interface for making predictions
* 📁 Organized and maintainable project structure

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Machine Learning & Data Processing

* Pandas
* NumPy
* Scikit-learn

### Application

* Streamlit

### Development Tools

* Git
* GitHub
* Virtual Environment

---

## 📂 Project Structure

```text
Laptop_Price_Prediction/
│
├── artifacts/
│   └──             # Generated datasets, models and other ML artifacts
│
├── laptop_price/
│   │
│   ├── components/
│   │   └──         # Data ingestion and transformation components
│   │
│   ├── entity/
│   │   └──         # Configuration and data-related entities
│   │
│   ├── pipeline/
│   │   └──         # Training pipeline and workflow orchestration
│   │
│   ├── prediction/
│   │   └──         # Prediction-related modules
│   │
│   ├── __init__.py
│   ├── config.py   # Project configuration
│   ├── exception.py # Custom exception handling
│   ├── logger.py   # Logging configuration
│   └── utils.py    # Utility/helper functions
│
├── prediction/
│   └── models/     # Saved/trained model files
│
├── .gitignore
├── README.md
├── app.py          # Application entry point
├── check_model.py  # Model validation/checking utility
├── main.py         # Main project entry point
└── requirements.txt
```

---

## 🔍 Project Modules

### 1. Components

The `components` module contains the core data-processing components of the machine learning workflow.

It is responsible for operations such as:

* Data ingestion
* Data preprocessing
* Data transformation
* Preparing data for model training

---

### 2. Entity

The `entity` module contains project-specific configuration and data structures used throughout the ML pipeline.

This helps maintain a clean separation between configuration, data, and processing logic.

---

### 3. Pipeline

The `pipeline` module manages the overall machine learning workflow.

It connects the different stages of the project, including:

```text
Data → Transformation → Training → Evaluation → Model
```

---

### 4. Prediction

The `prediction` module contains the logic required to use the trained machine learning model for making predictions on new laptop specifications.

---

### 5. Configuration

The `config.py` file contains project configuration settings such as paths and other parameters required by different modules.

Centralizing configuration makes the project easier to maintain and modify.

---

### 6. Logging

The `logger.py` module provides logging functionality to track the execution of different stages of the project.

Logging helps with:

* Debugging
* Monitoring
* Tracking pipeline execution
* Identifying errors

---

### 7. Exception Handling

The `exception.py` module provides custom exception handling for the project.

This allows errors to be handled in a structured way and makes debugging easier.

---

### 8. Utilities

The `utils.py` module contains reusable helper functions used by different parts of the project.

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/AkhileshPatil07/Laptop_Price_Prediction.git
cd Laptop_Price_Prediction
```

### 2. Create a Virtual Environment

#### Windows

```bash
python -m venv venv
```

Activate the environment:

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Run the Main Pipeline

```bash
python main.py
```

### Run the Application

```bash
streamlit run app.py
```

After starting Streamlit, open the URL displayed in the terminal to access the application.

---

## 📊 Prediction Process

The application takes laptop specifications as input and passes them through the trained preprocessing and machine learning pipeline.

```text
Laptop Specifications
        ↓
Input Processing
        ↓
Feature Transformation
        ↓
Trained ML Model
        ↓
Predicted Laptop Price
```

---

## 📦 Model Artifacts

The `artifacts/` and model-related directories are used to store generated files required by the machine learning workflow.

These may include:

* Processed datasets
* Trained machine learning models
* Preprocessing objects
* Transformation artifacts
* Other generated pipeline files

---

## 🧪 Model Checking

The project includes `check_model.py`, which can be used to verify or inspect the trained model and its associated artifacts.

```bash
python check_model.py
```

---

## 🎯 Project Objectives

The main objectives of this project are:

* Build an end-to-end machine learning prediction system.
* Understand the complete ML workflow from data processing to prediction.
* Implement a modular and maintainable project architecture.
* Develop reusable data transformation and prediction components.
* Deploy the prediction system through a user-friendly application.
* Practice production-oriented machine learning development.

---

## 🔮 Future Improvements

Possible future enhancements include:

* Deploy the application to a cloud platform.
* Add automated model retraining.
* Add model performance dashboards.
* Implement experiment tracking.
* Add Docker-based deployment.
* Improve UI/UX of the prediction application.
* Add API-based prediction using FastAPI or Flask.
* Implement CI/CD for automated deployment.

---

## 👨‍💻 Author

**Akhilesh Patil**

Data Scientist with hands-on experience in Python, SQL, Machine Learning, Data Analysis, and Deep Learning.

---

## 📄 License

This project is distributed under the MIT License. See the `LICENSE` file for more information.

---

⭐ If you find this project useful, consider giving the repository a star!

