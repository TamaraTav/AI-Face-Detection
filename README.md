# AI Face Detection

<div align="center">
  <img width="720" height="560" alt="download" src="https://github.com/user-attachments/assets/44c012eb-12cf-4323-891e-5fe120cd0f94" />
</div>

A real-time face detection application built with JavaScript and the face-api.js library. This project detects faces, facial landmarks, and expressions from live video feed using your webcam.

## Features

- **Real-time Face Detection**: Detects multiple faces in live video stream
- **Facial Landmarks**: Shows 68 facial landmark points on detected faces
- **Emotion Recognition**: Analyzes and displays facial expressions (happy, sad, angry, etc.)
- **Live Video Processing**: Processes video feed in real-time with 100ms intervals
- **Responsive Design**: Adapts to different screen sizes

## Technologies Used

- **face-api.js**: JavaScript API for face detection and recognition
- **HTML5 Canvas**: For rendering detection overlays
- **WebRTC**: For accessing webcam video stream
- **TinyFaceDetector**: Lightweight face detection model

## Models Included

- `tiny_face_detector_model`: Lightweight face detection
- `face_landmark_68_model`: 68-point facial landmark detection
- `face_recognition_model`: Face recognition and encoding
- `face_expression_model`: Facial expression analysis

## Installation

1. Clone or download this repository
2. Ensure all files are in the same directory:
   - `index.html`
   - `script.js`
   - `face-api.min.js`
   - `models/` folder with all model files

## Usage

1. Open `index.html` in a modern web browser
2. Allow camera access when prompted
3. The application will automatically:
   - Load the required AI models
   - Start your webcam
   - Begin real-time face detection
   - Display facial landmarks and expressions

## Requirements

- Modern web browser with WebRTC support
- Webcam/camera access
- Internet connection (for initial model loading)

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Performance Notes

- The application runs detection every 100ms for smooth real-time performance
- Performance may vary based on device capabilities and number of faces detected
- For best results, ensure good lighting conditions

## Credits

- **face-api.js**: [https://github.com/justadudewhohacks/face-api.js](https://github.com/justadudewhohacks/face-api.js)
- Models provided by the face-api.js library

## License

This project is for educational purposes. Please refer to the face-api.js library license for model usage terms.
