# GestureVoiceAI – Real-Time Gesture Recognition and Speech

## Project Overview
GestureVoiceAI is a Python-based application that recognizes hand gestures in real time and supports speech output, helping make communication more accessible.

## Features
- Real-time hand gesture recognition using a webcam
- Hand landmark processing with MediaPipe
- Machine learning model for gesture classification
- Speech output for recognized gestures
- Graphical user interface

## Technologies Used
- Python
- OpenCV
- MediaPipe
- TensorFlow / Keras
- NumPy
- Scikit-learn
- Speech processing libraries

## Project Structure
- `gui.py` – graphical user interface and application entry point
- `gesture_detector.py` – gesture detection logic
- `collect_dataset.py` – gesture dataset collection
- `train_model.py` – model training
- `realtime_system.py` – real-time processing
- `speech_engine.py` – speech functionality
- `models/` – trained model and label encoder
- `gesture_images/` – gesture reference images
- `gesture_dataset.csv` – gesture dataset

## How to Run

1. Install Python 3.12.
2. Clone this repository and open the project folder.
3. Create and activate a virtual environment.
4. Install the required Python packages.
5. Run the application:

```bash
python gui.py
```

Note: Create a `requirements.txt` file listing the project's dependencies before following the installation steps. A working webcam is required for real-time recognition.

## Future Improvements
- Improve recognition accuracy
- Expand gesture vocabulary
- Enhance accessibility and user experience

## Author
Vaishnavi Desale
