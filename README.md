💎  **Diamond Price Prediction using Machine Learning** 💎

This is an end-to-end machine learning project that predicts the price of a diamond based on its physical and categorical properties. The model is trained using multiple regression algorithms, and the best-performing model is selected automatically.

A Flask-based web interface is also included for real-time user prediction.

📌 Project Goals

Analyze and clean dataset

Transform categorical values using encoding

Train multiple regression models

Select the best model based on accuracy (R² Score)

Deploy prediction using a Flask web app

🧠 Machine Learning Models Used
| Model                   | Used in Project | Type                    |
| ----------------------- | --------------- | ----------------------- |
| Linear Regression       | ✔               | Basic Regression        |
| Ridge Regression        | ✔               | Regularized Regression  |
| Lasso Regression        | ✔               | Feature Selection       |
| ElasticNet              | ✔               | Hybrid of Ridge + Lasso |
| Decision Tree Regressor | ✔               | Non-linear model        |


📌 The best model is selected based on the highest R² score.

The dataset contains 193573 records of diamonds with the following features:
📊 Dataset Details
| Feature              | Description                     |
| -------------------- | ------------------------------- |
| Carat                | Weight of diamond               |
| Cut                  | Quality (Fair → Ideal)          |
| Color                | Grade from D (Best) → J (Worst) |
| Clarity              | Purity (IF → I1)                |
| Depth                | Depth percentage                |
| Table                | Flat top facet (%)              |
| Dimensions (x, y, z) | Size in millimeters             |
| Price                | 💰 Target variable              |

Dataset Source: [Kaggle Diamonds Dataset](https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv)

🧰 Technology Stack

| Category     | Tools                       |
| ------------ | --------------------------- |
| Language     | Python                      |
| ML Libraries | Scikit-Learn, NumPy, Pandas |
| Frontend     | HTML, CSS                   |
| Backend      | Flask                       |
| Model Saving | Pickle                      |

📁 Project Folder Structure

📦 Diamond-Price-Prediction
│── application.py
│── requirements.txt
│── setup.py
│── README.md
│── 📂 src
│   ├── utils.py
│   ├── logger.py
│   ├── exception.py
│   ├── data_ingestion.py
│   ├── data_transformation.py
│   └── model_trainer.py
│── 📂 templates
│   └── index.html
│── 📂 artifacts
│   └── model.pkl

⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/<your-username>/Diamond-Price-Prediction.git
cd Diamond-Price-Prediction

2️⃣ Create & activate virtual environment

Windows

python -m venv venv
venv\Scripts\activate

Linux/Mac

python3 -m venv venv
source venv/bin/activate

3️⃣ Install dependencies

pip install -r requirements.txt

4️⃣ Run Flask App

python application.py

Open the browser & go to:

👉 http://127.0.0.1:5000/

📈 Model Performance

| Model                   | R² Score          |
| ----------------------- | ----------------- |
| Linear Regression       | ~0.93             |
| Ridge                   | ~0.94             |
| Lasso                   | ~0.92             |
| ElasticNet              | ~0.93             |
| Decision Tree           | ~0.97             |
| **Best Model Selected** | ⭐ Decision Tree ⭐ |

📜 License

Licensed under MIT License.

👤 Author

✦ Anish Das

📧 anishdasad2003@gmail.com

⭐ If this project helped you — please star the repo!
