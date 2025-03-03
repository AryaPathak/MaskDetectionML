

# Mask Detection using CNN and OpenCV

This project aims to detect whether a person is wearing a mask or not
using Convolutional Neural Networks (CNN) and OpenCV.
The model is trained on facial images and predicts mask-wearing status in
real-time using a webcam.

## Features
- Real-time face mask detection using OpenCV.
- CNN-based model for classification.
- Trained on a dataset of masked and unmasked faces.
- Optimized for accuracy and performance.

## Technologies Used
- Python
- OpenCV
- TensorFlow/Keras (for CNN)
- NumPy & Pandas
- Matplotlib (for visualization)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/AryaPathak/MaskDetectionML
   cd mask-detection
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Run the detection script:
   ```sh
   python detect_mask.py
   ```

## Dataset
The dataset consists of labeled images of faces with and without masks. You can use datasets from sources like:
- [Kaggle Face Mask Dataset](https://www.kaggle.com/)
- Custom images collected from various sources.

## Model Training
Train the CNN model using:
```sh
python train_model.py
```
The trained model will be saved as `mask_detector.model`.

## Usage
- Run the script to detect masks in real-time.
- The output will display faces with bounding boxes and labels (`Mask` or `No Mask`).

## Future Improvements
- Improve model accuracy with a larger dataset.
- Deploy as a web or mobile application.
- Implement edge computing for real-time performance.

## License
This project is open-source and available under the MIT License.


```
