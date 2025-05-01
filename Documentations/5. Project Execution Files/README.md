# **Uncovering the Hidden Treasures of the Mushroom Kingdom: A Classification Analysis**

## **Project Description**
- This project focuses on the classification of different types of mushrooms found in various regions of the world. The classification is based on images of mushrooms, and the goal is to use deep learning techniques for accurate species recognition.
- By applying transfer learning and deep learning methodologies, the project aims to accurately classify mushrooms into three main categories: Boletus, Lactarius, and Russula. These categories represent different types of mushrooms found in diverse regions worldwide. The ultimate objective is to develop a robust and reliable classification system for mushroom species recognition based on their visual attributes.

## **Screenshots**

### Home Page:
<p align="center">
 <img src="https://drive.google.com/uc?export=view&id=1xx0FDbah3uF6loz7lk7S477n_RI3yLyI" width="800" height="auto" alt="Your Image Description">

</p>

### Mushroom Classification Result:
<p align="center">
 <img src="https://drive.google.com/uc?export=view&id=1UprNPKGUj-xzPQNwcYuEQQR4ZTS6x8kM" width="800" height="auto" alt="Classification Results Display">
</p>

## **Installation and Setup**

### Using Conda (Recommended)

```bash
# Create a new conda environment
conda create -n mushroom_classifier python=3.10.16

# Activate the environment
conda activate mushroom_classifier

# Clone the repository
git clone https://github.com/prajwalnikam/AI-Mushroom-Classification-Analysis.git
cd AI-Mushroom-Classification-Analysis-master

# Install dependencies
pip install -r requirements.txt
```

### Using Python venv

```bash
# Create a virtual environment
python -m venv mushroom_env

# Activate the environment
# On Windows:
mushroom_env\Scripts\activate
# On macOS/Linux:
source mushroom_env/bin/activate

# Install dependencies
pip install -r requirements.txt
```

## **Running the Application**

```bash
# Navigate to the Flask directory
cd Flask

# Start the web application
python app.py

# The application will be available at http://localhost:5000
```

## **Project Structure**
```
AI-Mushroom-Classification-Analysis-master/
├── Dataset/
│   ├── test/          # Test dataset
│   └── train/         # Training dataset
├── Flask/
│   ├── static/        # Static assets (CSS, JS, images)
│   ├── templates/     # HTML templates
│   ├── uploads/       # User uploaded images
│   └── app.py         # Main Flask application
├── IBM Files/         # Files related to IBM Cloud deployment
├── images/            # Project images and screenshots
├── Training files/    # Training scripts and notebooks
├── Mushroom Classification Model.h5   # Trained model file
├── Mushroom Classification Project Demonstration.mp4  # Demo video
├── README.md          # Project documentation
└── requirements.txt   # Project dependencies
```

## **Technologies Used**
- Python 3.10
- TensorFlow/Keras
- Flask
- HTML/CSS/JavaScript
- OpenCV
- NumPy/Pandas

## **Model Architecture**
The classification model is built using transfer learning with pre-trained neural networks. The trained model is saved as `Mushroom Classification Model.h5` in the root directory.

## **Dataset**
The dataset is organized in the Dataset folder with separate test and train directories. It consists of images of three main mushroom genera:
- Boletus
- Lactarius
- Russula


## **Future Improvements**
- Expand classification capabilities to include more mushroom species
- Implement mobile application for field identification
- Add detailed information about each mushroom species
- Integrate geographical data to enhance classification accuracy

## **Conclusion**
The mushroom classification project utilizes deep learning and transfer learning techniques to build an accurate and efficient classification system. By leveraging pre-trained models and a comprehensive mushroom dataset, we aim to contribute to the field of mushroom recognition and promote the understanding of mushroom species diversity in different regions.

