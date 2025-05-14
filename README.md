**ANN Customer Churn Prediction**

This project utilizes an Artificial Neural Network (ANN) to predict customer churn based on various customer attributes. The model is trained using a dataset of bank customers and deployed as an interactive web application using Streamlit.

🔗 Live Demo

Check out the live application here: https://anncustomerchurn-xejbx35hkv9oepjmpxyfdx.streamlit.app/

📂 Repository

GitHub Repository: https://github.com/YathinChandra64/ANN_Customer_Churn

📊 Dataset

The model is trained on the Churn_Modelling.csv dataset, which includes features such as:

Customer ID

Credit Score

Geography

Gender

Age

Tenure

Balance

Number of Products

Has Credit Card

Is Active Member

Estimated Salary

Exited (Target Variable)

🛠️ Technologies Used

Python: Programming language used for model development.

TensorFlow / Keras: Libraries used to build and train the ANN model.

Pandas & NumPy: For data manipulation and numerical operations.

Scikit-learn: For preprocessing and evaluation metrics.

Streamlit: Framework used to deploy the model as a web application.

🚀 Getting Started

Prerequisites

Ensure you have the following installed:

Python 3.x (Preferred to use Python 3.10.x or 3.11.x)

pip (Python package installer)

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/YathinChandra64/ANN_Customer_Churn.git
cd ANN_Customer_Churn
Install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
Running the Application Locally
To run the Streamlit application locally:

bash
Copy
Edit
streamlit run app.py
This will start the application, and you can access it in your web browser at http://localhost:8501/.

📁 Project Structure

ANN_Customer_Churn/
├── app.py                   # Streamlit application
├── Churn_Modelling.csv      # Dataset
├── experiments.ipynb        # Notebook for model experimentation
├── prediction.ipynb         # Notebook for predictions
├── model.h5                 # Trained ANN model
├── scaler.pkl               # Scaler for feature normalization
├── label_encoder_gender.pkl # Label encoder for 'Gender'
├── ohe_geo.pkl              # One-hot encoder for 'Geography'
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation

📈 Model Performance
The ANN model was trained and evaluated using appropriate metrics. For detailed performance metrics and evaluation, refer to the experiments.ipynb notebook.

🧠 How It Works
Data Preprocessing: Categorical variables like 'Gender' and 'Geography' are encoded using label encoding and one-hot encoding, respectively. Features are scaled for optimal model performance.

Model Training: An ANN is constructed using Keras, trained on the preprocessed data to predict the likelihood of customer churn.

Model Deployment: The trained model is integrated into a Streamlit application, allowing users to input customer details and receive churn predictions in real-time.
