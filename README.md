🧠 Uncovering the Hidden Treasures of the Mushroom Kingdom

A Classification Analysis Using Deep Learning

📌 Overview
This project focuses on classifying mushroom species using deep learning techniques. By leveraging transfer learning, the model accurately categorizes mushrooms into three genera:

Boletus

Lactarius

Russula

The goal is to build a robust visual classification system that helps recognize mushrooms found in various regions worldwide.

🖼️ Demo Screenshots
🔹 Home Page

<p align="center"> 
  <img src="https://drive.google.com/uc?export=view&id=1dXUPq0OiRTV-h09iJhoJWNhBYuqw6VjY" width="800" alt="Home Page Screenshot">
</p>
🔹 Classification Result
<p align="center">\
  <img src="https://drive.google.com/uc?export=view&id=1fgDNk36_GoGV3AdLgkA0_0z7ZEo7gtcz" width="800" alt="Classification Results Screenshot">
</p>
🛠️ Technologies Used
Python 3.10.6

TensorFlow / Keras

Flask (Backend)

HTML / CSS / JavaScript (Frontend)

OpenCV

NumPy & Pandas

🧠 Model Details
The mushroom classifier uses transfer learning with a pre-trained neural network.
The final model is saved as:

bash
Copy
Edit
Mushroom Classification Model.h5
🗂️ Project Directory Structure
graphql
Copy
Edit
AI-Mushroom-Classification-Analysis-master/
├── Dataset/ # Image dataset (train/test)
├── Flask/ # Web application (Flask)
│ ├── static/ # JS and CSS files
│ ├── templates/ # HTML templates
│ ├── uploads/ # Uploaded user images
│ └── app.py # Main Flask app
├── IBM Files/ # IBM Cloud deployment setup
├── Training files/ # Training scripts and notebooks
├── requirements.txt # Python dependencies
└── README.md # Project documentation
⚙️ Installation & Setup
📦 Using Conda (Recommended)
bash
Copy
Edit
conda create -n mushroom_classifier python=3.10
conda activate mushroom_classifier
git clone https://github.com/Rohitmh09/AI-Mushroom-Classification-Analysis.git
cd AI-Mushroom-Classification-Analysis-master
pip install -r requirements.txt
🐍 Using Python venv
bash
Copy
Edit
python -m venv mushroom_env

# Windows:

mushroom_env\Scripts\activate

# macOS/Linux:

source mushroom_env/bin/activate

pip install -r requirements.txt
Note: Make sure to install Flask and TensorFlow separately if not included in the requirements.

🚀 Running the Application
bash
Copy
Edit
cd Flask
python app.py
Open your browser and go to:
👉 http://localhost:5000

📁 Dataset Overview
The dataset includes labeled images of three mushroom genera:

🍄 Boletus

🍄 Lactarius

🍄 Russula

Each category is split into train and test directories for training the classification model.

🔮 Future Enhancements
Add more mushroom species for classification

Launch a mobile app for real-time field identification

Provide detailed biological data for each species

Integrate geographical metadata to boost model accuracy

✅ Conclusion
This project demonstrates the power of deep learning and transfer learning in biological image classification. With accurate species recognition, it lays the groundwork for educational tools, conservation efforts, and field applications related to mushroom identification and biodiversity.
