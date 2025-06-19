# Sign Language Translation Project

This project is designed to translate hand gestures for sign language using machine learning models and image processing. It leverages hand gesture recognition to facilitate sign language translation in real-time.

## 📄 Research Report

Read the full research paper explaining the background, implementation, and results of this project:
[📥 Download the PDF](./docs/Research%20Paper.pdf)

## Features
- Hand gesture recognition using `hands_gesture_recog.py`.
- Pre-trained model for gesture classification stored in `model.pkl`.
- Scripts for data collection and image preprocessing.
- Jupyter notebook for model training (`train.ipynb`).

## Getting Started

### Prerequisites
- Python 3.x
- Install the required libraries by running:
    ```
    pip install -r requirements.txt
    ```

### Running the Project
1. Ensure that you have installed all dependencies from the `requirements.txt` file.
2. To run the hand gesture recognition, use:
    ```
    python hands_gesture_recog.py
    ```

## Project Structure
- **get_data.py**: Script to collect gesture data.
- **get_image.py**: Script to preprocess images.
- **hands_gesture_recog.py**: Main script for hand gesture recognition.
- **train.ipynb**: Jupyter notebook for training the gesture recognition model.
- **test_mediapipe.py**: Script to test MediaPipe hand tracking.
- **model.pkl**: Pre-trained model for gesture classification.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

This project is a part of a portfolio aimed at demonstrating skills in machine learning, computer vision, and Python programming.
