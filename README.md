# 🚧 Road Pothole Detection Using YOLOv8 Custom Segmentation 🚧

Welcome to the **Road Pothole Detection** project, where we leverage the power of **YOLOv8 custom segmentation** to accurately identify potholes in road footage. This project aims to contribute to road safety by enabling real-time detection and visualization of potholes, aiding in road maintenance and potentially preventing accidents.

---

## 🔍 **Project Overview**

In this project, we use **YOLOv8** for custom segmentation to detect and mark potholes in videos. With the integration of **OpenCV** and **cvzone**, we can highlight the contours of detected potholes and display them in real time. This solution is designed to help authorities identify road damage quickly and efficiently, ensuring safer road conditions for all vehicles.

---

## 🎯 **Key Features**
- **Real-Time Pothole Detection**: Analyzes video footage and detects potholes in real-time.
- **YOLOv8 Custom Segmentation**: Leverages a custom-trained YOLOv8 model for precise segmentation of road potholes.
- **Contours and Bounding Boxes**: Highlights the detected potholes using bounding boxes and contours for better visualization.
- **High Accuracy**: Fine-tuned model to detect road damage under various conditions.
- **Scalable Solution**: Can be implemented in smart infrastructure for road monitoring and safety management.

---

## 🛠️ **Technologies Used**
- **YOLOv8**: Custom-trained segmentation model for object detection.
- **OpenCV**: Used for image processing and real-time visualization.
- **cvzone**: For displaying bounding boxes and labels with enhanced visualization features.
- **NumPy**: Handling numerical operations and image processing tasks.

---

## 📂 **Project Structure**

```bash
.
├── best.pt                    # Trained YOLOv8 model for pothole detection
├── p.mp4                      # Sample video footage for testing
├── main.py                    # Main script for running the detection
└── README.md                  # Project documentation
```

---

## 🚀 **How to Run the Project**

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/road-pothole-detection.git
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Script
```bash
python main.py
```

Ensure that you have the video file (`p.mp4`) and the model weights (`best.pt`) in the correct paths.

---

## 🧠 **How It Works**

1. The video stream is loaded using OpenCV.
2. YOLOv8 detects potholes by segmenting the video frame and generating masks.
3. **Contours** are drawn around the detected potholes, and the labels are displayed using **cvzone**.
4. The final output shows the potholes in the frame, with real-time updates.

---

## 🎥 **Demo**

Check out a quick demo of the pothole detection in action:

![Demo Video](https://github.com/yourusername/road-pothole-detection/demo.gif)

---

## 🤖 **Model Training**

The YOLOv8 model was trained on a custom dataset of road footage featuring potholes. The dataset was labeled using **segmentation masks**, allowing the model to precisely detect and segment road potholes.

For more details on training, check out the training script [here](link_to_training_script).

---

## 🌟 **Contributing**

Contributions are welcome! If you have any ideas to improve the model or the project, feel free to submit a pull request or open an issue.

---

## 📬 **Contact**

If you have any questions, feel free to reach out:

- **LinkedIn**: [Sayed Ali Elsayed](https://www.linkedin.com/in/sayed-ali-482668262/)
- **Email**: [saiedhassaan2@gmail.com](mailto:saiedhassaan2@gmail.com)

---

## 📜 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
