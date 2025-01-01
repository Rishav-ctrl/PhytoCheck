# PhytoCheck: Plant Disease Detection

**PhytoCheck** is an AI-based mobile application designed to detect diseases in plant leaves, specifically for Potato and Tomato plants. This project demonstrates how machine learning can help farmers and gardeners identify plant diseases early, improving crop health and productivity.

## Project Overview

This project includes the following components:

1. **Dataset Preparation**
   - Data sourced from Kaggle for potato and tomato leaf diseases.
   - Images labeled as `Healthy` or `Diseased`.

2. **AI Model**
   - Built using TensorFlow/Keras.
   - Trained on a dataset of leaf images.
   - Achieves high accuracy in disease classification.

3. **Mobile Application**
   - Frontend: React Native.
   - Backend: Flask or Node.js API.
   - Provides a user-friendly interface for disease detection.

## Features

- Detect diseases in potato and tomato plants.
- Upload leaf images via the app.
- Get instant results on the health status of the plant.

## Installation

### Requirements

- Python 3.8+
- TensorFlow, Keras
- Flask or Node.js
- React Native CLI
- Kaggle API for dataset download

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Rishav-ctrl/PhytoCheck.git
   cd PhytoCheck
   ```

2. Set up the environment:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset:
   - Configure Kaggle API by adding `kaggle.json` to your working directory.
   - Run the following command to download the dataset:
     ```bash
     !kaggle datasets download -d puneet6060/plant-disease-detection
     ```

4. Train the AI model:
   ```bash
   python train_model.py
   ```

5. Start the backend server:
   ```bash
   python app.py
   ```

6. Run the mobile app using React Native:
   ```bash
   npx react-native run-android
   ```

## Usage

- Open the PhytoCheck app.
- Capture or upload an image of a plant leaf.
- Get real-time disease detection results.

## Project Structure

```
PhytoCheck/
├── dataset/                # Dataset folder
├── models/                # Trained AI models
├── backend/               # Backend API (Flask or Node.js)
├── mobile_app/            # React Native frontend
├── train_model.py         # Training script for the AI model
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```

## Results

- High accuracy in detecting healthy and diseased leaves.
- Robust performance across various image conditions.

## Future Work

- Add support for more plant types.
- Improve model accuracy with larger datasets.
- Enhance the mobile app with real-time camera integration.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Kaggle for providing the dataset.
- TensorFlow and Keras for making AI development accessible.
- Open-source contributors for their amazing tools and libraries.
