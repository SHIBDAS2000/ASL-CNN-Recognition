
# American Sign Language Recognition Using CNNs

This project develops a Convolutional Neural Network (CNN) to recognize American Sign Language (ASL) letters (A-Z) from images, achieving 89.97% training accuracy and 78.73% validation accuracy.

## Project Overview
- **Goal**: Translate ASL hand gestures into text using a CNN.
- **Tools**: Python, TensorFlow/Keras, OpenCV, Google Colab.
- **Dataset**: [Link to dataset, e.g., Kaggle ASL Alphabet].
- **Deliverables**: Jupyter Notebook, trained model (.h5), confusion matrix, real-time demo.

## How to Run
1. Clone this repo: `git clone [repo-link]`.
2. Install dependencies: `pip install -r requirements.txt`.
3. Open `ASL_CNN.ipynb` in Jupyter or Colab.
4. Load the `.h5` model for predictions or retrain using the notebook.
5. Run `real_time_detection.py` for webcam-based demo (requires OpenCV).

## Results
- **Training Accuracy**: 89.97%.
- **Validation Accuracy**: 78.73%.
- **Confusion Matrix**: Strong diagonal dominance; minor confusions (e.g., 'I' vs. 'J').
- **Real-Time Demo**: Recognizes ASL letters via webcam input.

## Files
- `ASL_CNN.ipynb`: Full code for data prep, training, and evaluation.
- `model.h5`: Trained CNN model [or Drive link].
- `screenshots/`: Training plots, confusion matrix, demo images.
- `report.pdf`: 10-slide project summary.

## Future Work
- Increase dataset size for better generalization.
- Optimize model for mobile or edge devices.

## Contact
Shibdas Bhattacharya | https://www.linkedin.com/in/shibdasbhattacharya/

Feel free to explore the code and provide feedback!
