# SightIQ - Real-Time AI Object Detection

SightIQ is a powerful web-based application that leverages artificial intelligence to detect and identify objects in real-time using your device's camera. Built with modern web technologies, it provides instant object recognition with detailed product information and metadata.

![SightIQ Demo](demo.gif)

## 🌟 Features

- **Real-time Object Detection**: Instantly identify objects using your device's camera
- **Multiple Object Categories**: Detect various items including:
  - Electronics (laptops, phones, TVs)
  - Fashion items (glasses, watches, hats)
  - Vehicles (cars, trucks, buses)
  - Personal items (bottles, books)
  - And many more!

- **Rich Metadata Display**:
  - Brand information
  - Product titles
  - Price ranges
  - Brief descriptions

- **User-Friendly Interface**:
  - Clean, modern Apple-inspired design
  - Smooth animations and transitions
  - Responsive layout for all devices
  - Camera switching capability

## 🚀 Technologies Used

- **Frontend**:
  - HTML5
  - CSS3 with TailwindCSS
  - JavaScript (ES6+)
  - TensorFlow.js
  - COCO-SSD Model

- **AI/ML**:
  - TensorFlow.js for model inference
  - COCO-SSD pre-trained model
  - Real-time object detection

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sightiq.git
   cd sightiq
   ```

2. Open `index.html` in a modern web browser:
   ```bash
   # Using Python's built-in server
   python -m http.server 8000
   # Or using Node's http-server
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## 📱 Usage

1. Allow camera access when prompted
2. Point your camera at objects you want to detect
3. View real-time detection results with metadata
4. Use the camera switch button to toggle between front and back cameras
5. Share your detections using the share button

## 🔧 Configuration

The application can be configured by modifying the following constants in `index.html`:

```javascript
const CONFIG = {
    CONFIDENCE_THRESHOLD: 0.6,  // Detection confidence threshold
    MAX_DETECTIONS: 20,         // Maximum number of simultaneous detections
    CANVAS_SIZE: { width: 640, height: 480 }  // Detection canvas size
};
```


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

shodeindeenoch06@gmail.com


## 🙏 Acknowledgments

- TensorFlow.js team for the amazing ML framework
- COCO dataset contributors
- All contributors and users of SightIQ 