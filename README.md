🕵️‍♂️ Fake Job Post Detection

A machine-learning–powered web application built with Flask to detect whether a job posting is real or fraudulent using ML techniques and a trained classification model.

🚀 Features

🔍 Detect fake job posts using a trained ML model

🧠 TF-IDF vectorization for text processing

🤖 Machine Learning classifier stored as .pkl

🌐 Flask web app with a clean UI

📁 Fully reproducible code and dataset

📂 Project Structure
Fake_Job_Post_Detection
│── app.py                  # Flask application
│── model.py                # ML model training script
│── Fake_Job_Post_Detection.csv  # Dataset
│── job_fraud_model.pkl     # Trained ML model
│── tfidf_vectorizer.pkl    # TF-IDF vectorizer
│── templates/              # HTML templates
│── static/                 # CSS, images, etc.
│── bg1.jpg                 # Background image
│── README.md               # Documentation

🧠 How It Works

The system takes job description text as input.

Text is transformed using a TF-IDF vectorizer.

The ML classifier predicts whether the job post is:

✔️ Real

❌ Fake

Results are displayed through the Flask web UI.

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/Fake_Job_Post_Detection.git
cd Fake_Job_Post_Detection

2️⃣ Install dependencies
pip install -r requirements.txt


(If requirements.txt is missing, use this:)

pip install flask pandas scikit-learn numpy

3️⃣ Run the Flask app
python app.py

4️⃣ Open your browser
http://127.0.0.1:5000

📊 Dataset

The project uses a dataset of job descriptions labeled as real or fraudulent.
File: Fake_Job_Post_Detection.csv

📦 Model Training

The machine-learning pipeline (found in model.py) includes:

Text cleaning

TF-IDF vectorization

Model training (e.g., Logistic Regression / SVM / etc.)

Model serialization into job_fraud_model.pkl

Run training:

python model.py

🖼️ UI Preview

The web interface displays:

A form to enter job data

Prediction results (Real / Fake)

🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss your ideas.
