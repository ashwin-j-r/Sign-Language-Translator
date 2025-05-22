# Sign Language Recognition

This project aims to bridge the communication gap between the hearing and hearing-impaired communities through an advanced sign language recognition system. By leveraging deep learning techniques, the system can accurately interpret sign gestures in real time.

## 🚀 Overview

The system integrates multiple models:
- **YOLOv5s**: Real-time detection and classification of hand gestures from images.
- **TensorFlow LSTM**: Sequence modeling for recognizing sign language words using hand landmark data.
- **Keras CNN**: Classification of grayscale images to identify individual sign language letters.

## 🔧 Features

- High accuracy in gesture classification (up to 94%).
- Real-time gesture recognition and feedback.
- User-friendly interface for both letters and words.
- Data preprocessing using MediaPipe and grayscale conversion.

## 🛠️ Technologies Used

- Python  
- TensorFlow & Keras  
- YOLOv5  
- MediaPipe  
- OpenCV  
- CUDA (for GPU acceleration)

## 📈 Performance Summary

| Model              | Accuracy | Precision |
|-------------------|----------|-----------|
| TensorFlow LSTM   | 94% (words), 92% (letters) | 92% |
| Keras CNN         | 93%      | 92%       |
| YOLOv5s           | 89%      | 88%       |

## 🔮 Future Enhancements

- Expand vocabulary and support for regional sign languages.
- Improve real-time performance on resource-constrained devices.
- Integrate multimodal data (e.g., depth, audio).
- Introduce adaptive learning based on user feedback.

## 🤝 Contribution

This project was developed as part of an academic initiative to enhance accessibility through AI. Future contributions are welcome to extend its capabilities and impact.

