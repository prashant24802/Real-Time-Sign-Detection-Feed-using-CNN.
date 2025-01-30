# Real-Time Sign Language Detection Using CNN

## Description
This project aims to detect and interpret sign language gestures in real-time using a Convolutional Neural Network (CNN). The system captures video input from a webcam, processes the frames to detect hand gestures, and translates them into text or speech. This can be particularly useful for bridging communication gaps between sign language users and non-signers.

## Features
- Real-time sign language gesture detection.
- Pre-trained CNN model for accurate gesture recognition.
- Supports a subset of ASL (American Sign Language) gestures.
- Outputs detected gestures as text or speech.
- Easy-to-use interface for testing and demonstration.

## Installation
Follow these steps to set up the project on your local machine.

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-time-sign-language-detection.git
   cd real-time-sign-language-detection
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the pre-trained model weights (if applicable) and place them in the `models/` directory.

4. (Optional) If you want to train the model yourself, follow the instructions in the `Training` section below.

## Usage
To run the real-time sign language detection system:

1. Start the application:
   ```bash
   python main.py
   ```

2. A window will open showing the webcam feed. Perform sign language gestures in front of the camera.

3. Detected gestures will be displayed as text on the screen and spoken aloud (if text-to-speech is enabled).

4. Press `q` to exit the application.

## Training the Model
If you want to train the CNN model on your own dataset:

1. Prepare your dataset:
   - Organize images of sign language gestures into folders, with each folder representing a specific gesture.
   - Place the dataset in the `data/` directory.

2. Run the training script:
   ```bash
   python train.py --data_path data/ --epochs 20 --batch_size 32
   ```

3. After training, the model weights will be saved in the `models/` directory. Update the `main.py` script to use the new model.

## Dataset
The model was trained on a subset of the [ASL Alphabet Dataset](https://www.kaggle.com/grassknoted/asl-alphabet). You can use this dataset or create your own.

## Contributing
We welcome contributions! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Submit a pull request with a detailed description of your changes.

## Acknowledgments
- Thanks to the creators of the ASL Alphabet Dataset for providing the data.
- This project was inspired by the need for better communication tools for the deaf and hard-of-hearing community.

## Contact
For questions or feedback, please reach out to:
- **Email** - [info.prashant248@gmail.com]
- **Project Repository** - (https://github.com/prashant24802/Real-Time-Sign-Detection-Feed-using-CNN.)

