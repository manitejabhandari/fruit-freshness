# Fruit Freshness Detection

A computer vision application that classifies fruits as **Fresh** or **Rotten** using deep learning and image classification techniques. The project combines TensorFlow-based model inference with a Streamlit web interface to provide an easy-to-use freshness detection system.

---

## Project Overview

Food spoilage is a major challenge in agriculture, retail, supply chain management, and household consumption. Manual inspection of fruit quality can be time-consuming, inconsistent, and difficult to scale.

This project explores how deep learning can be used to automate freshness detection by analyzing fruit images and classifying them into freshness categories.

The application enables users to upload an image and receive a freshness prediction through an interactive web interface.

---

## Problem Statement

Determining whether a fruit is fresh or rotten is often performed through visual inspection. In large-scale environments such as:

* Grocery stores
* Warehouses
* Agricultural facilities
* Food processing units

manual inspection becomes inefficient and prone to human error.

This project investigates how image classification models can assist in automating that process.

---

## Why This Project Exists

The project was built to:

* Apply computer vision techniques to a real-world problem.
* Explore deep learning workflows using TensorFlow and Keras.
* Develop an end-to-end machine learning application.
* Learn model deployment using Streamlit.
* Create a practical example of image-based classification.

---

## Key Features

* Fruit freshness classification from images
* TensorFlow and Keras-based deep learning model
* Interactive Streamlit web interface
* Image upload and prediction workflow
* Support for multiple fruit categories
* End-to-end machine learning pipeline

---

## System Workflow

```text
Input Image
     │
     ▼
Image Preprocessing
     │
     ▼
Feature Extraction
     │
     ▼
Deep Learning Model
     │
     ▼
Fresh / Rotten Prediction
     │
     ▼
Display Results in Streamlit
```

---

## Architecture Overview

```text
User Uploads Image
        │
        ▼
 Streamlit Frontend
        │
        ▼
 Image Preprocessing
        │
        ▼
 TensorFlow/Keras Model
        │
        ▼
 Prediction Engine
        │
        ▼
 Fresh / Rotten Output
```

---

## Tech Stack

### Machine Learning

* TensorFlow
* Keras
* NumPy

### Data Visualization

* Matplotlib

### Application Layer

* Streamlit

### Model Storage

* Pickle

### Programming Language

* Python

---

## Dataset Information

> Dataset information is currently not documented.

Recommended additions:

* Dataset source
* Number of images
* Fruit categories
* Fresh vs Rotten class distribution
* Training/Validation/Test split
* Data augmentation techniques

---

## Model Architecture

> Model architecture details are currently not documented.

Recommended additions:

* CNN architecture summary
* Number of layers
* Activation functions
* Input image dimensions
* Optimizer
* Loss function
* Training epochs
* Batch size

Example:

```text
Input Layer
   ↓
Convolution Layers
   ↓
Pooling Layers
   ↓
Dense Layers
   ↓
Softmax Output
```

---

## Project Structure

```text
Fruit-Freshness-Detection/
│
├── algoritm.py      # Core prediction logic
├── app1.py          # Streamlit application
├── file.py          # Utility functions
├── model.pkl        # Trained model
├── modell.py        # Model training script
├── new.py           # Experimental code
├── project.py       # Main project module
│
└── README.md
```

> Several filenames are currently ambiguous. Renaming files to descriptive names would improve maintainability.

Suggested naming:

```text
train_model.py
predict.py
app.py
utils.py
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/fruit-freshness-detection.git

cd fruit-freshness-detection
```

### Install Dependencies

```bash
pip install tensorflow streamlit numpy matplotlib pillow
```

---

## Running the Application

Launch the Streamlit application:

```bash
streamlit run app1.py
```

Open the generated local URL in your browser.

---

## Usage

1. Launch the Streamlit application.
2. Upload a fruit image.
3. Wait for model inference.
4. View freshness prediction.
5. Analyze results.

---

## Performance Metrics

> Performance metrics are not currently documented.

Recommended metrics:

| Metric    | Value |
| --------- | ----- |
| Accuracy  | TBD   |
| Precision | TBD   |
| Recall    | TBD   |
| F1 Score  | TBD   |

Adding these metrics would significantly improve project credibility.

---

## Engineering Challenges

Potential challenges addressed in this project include:

* Handling image preprocessing consistently.
* Training models on visually similar classes.
* Managing class imbalance.
* Reducing overfitting.
* Building an interactive inference interface.

Documenting actual challenges encountered would strengthen the repository.

---

## Technical Decisions & Trade-offs

### TensorFlow

Chosen for:

* Mature deep learning ecosystem
* Production readiness
* Strong community support

### Streamlit

Chosen for:

* Rapid prototyping
* Fast deployment
* Minimal frontend development requirements

### Pickle Serialization

Provides simple model persistence but may introduce compatibility issues across environments.

Alternative options:

* TensorFlow SavedModel
* HDF5 (.h5)

---

## Scalability Considerations

Current architecture is suitable for:

* Educational projects
* Research experiments
* Small-scale deployment

Future scaling options:

* REST API deployment
* Docker containerization
* Cloud inference services
* Batch image processing
* Edge deployment

---

## Future Improvements

* Improve classification accuracy
* Add transfer learning models
* Support additional fruit categories
* Deploy to cloud platforms
* Add confidence scores
* Add batch prediction functionality
* Introduce model monitoring
* Implement automated retraining pipelines

---

## Screenshots

Recommended additions:

### Application Interface

```text
[Upload Image Screen]
```

### Prediction Results

```text
[Fresh / Rotten Output]
```

### Model Evaluation

```text
[Confusion Matrix]
```

Screenshots significantly improve recruiter engagement.

---

## Resume-Worthy Highlights

* Built an end-to-end computer vision application using TensorFlow and Streamlit.
* Implemented image classification for fruit freshness detection.
* Developed a complete ML inference workflow from preprocessing to prediction.
* Integrated machine learning models into an interactive web application.
* Applied practical computer vision techniques to a real-world quality inspection problem.

---

## Interview Talking Points

Potential discussion topics:

* Dataset preparation and preprocessing strategy.
* CNN architecture design decisions.
* Overfitting mitigation techniques.
* Model evaluation methodology.
* Streamlit deployment architecture.
* Trade-offs between model accuracy and inference speed.
* Future productionization strategy.

---

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit changes.
4. Submit a pull request.

---

## License

Specify an open-source license such as:

* MIT License
* Apache 2.0 License
* GPL License

A license file should be added to the repository.
