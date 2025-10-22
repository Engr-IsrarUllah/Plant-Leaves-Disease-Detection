# Plant Leaves Disease Detection

Plant Leaves Disease Detection System is an innovative machine learning project that harnesses the power of Convolutional Neural Networks (CNN) and deep learning techniques to identify and classify diseases in plants. The primary objective is to offer farmers and agricultural experts a valuable tool for swift plant health diagnosis, facilitating timely intervention and minimizing the risk of crop loss.


## Project Structure 📂

The project comprises essential components:

- `Plant Leaves Disease Detection System.ipynb`: Jupyter Notebook with the code for model training.
- `main_app.py`: Streamlit web application for plant disease prediction.
- `plant_disease_model.h5`: Pre-trained model weights.
- `requirements.txt`: List of necessary Python packages.

## Installation 🚀

To run the project locally, follow these steps:

1. **Clone the repository:**

```bash
git clone https://github.com/Engr-IsrarUllah/Plant-Leaves-Disease-Detection.git
```

2. Navigate to the project directory:

```bash
cd Plant Leaves Disease Detection
```

3. **Install the required packages:**

```bash
pip install -r requirements.txt
```

4. **Run the Streamlit web application:**

```bash
streamlit run main_app.py
```

## Model Training 🧠

The model was trained using the `Plant Leaves Disease Detection System.ipynb` notebook. It employs a Convolutional Neural Network architecture to classify plant images into different disease categories. The trained model weights are saved in `plant_disease_model.h5`.

## Web Application 🌐

The web application (`main_app.py`) empowers users to interact with the trained model. Upload plant images, and the application provides real-time predictions regarding the health of the plant.

## Requirements 🛠️

- Keras==2.8.0
- numpy==1.21.4
- streamlit==1.18.0
- opencv-python-headless==4.5.3
- tensorflow==2.7.0
<br>
***Note: the libraries are updated with time***
