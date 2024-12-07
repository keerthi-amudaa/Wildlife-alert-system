# **Wildlife Monitoring and Alert System Using YOLOv8 🚨🌿**

This repository contains a **real-time wildlife monitoring and alert system** aimed at combating human-wildlife conflicts. The system detects animals in camera trap images using the **YOLOv8 algorithm** and sends email alerts with detected images when specific animals (like tigers, elephants, or leopards) are identified.

---

## **Features ✨**

- Real-time animal detection using YOLOv8.
- Automated email alerts with attached detection images.
- Trained on camera-trapped image dataset, acquired from the Karnataka Forest Department.
- Designed for human-wildlife conflict zones, such as forest borders.
- Integration with Roboflow for custom dataset training.
---


## **Installation 🛠️**

## Prerequisites

- Python 3.8+
- NVIDIA GPU with CUDA for training
- Libraries: ultralytics, opencv-python, smtplib, roboflow, matplotlib


1. **Clone the repository**:
  ```bash
git clone https://github.com/keerthi-amudaa/Wildlife-alert-system.git
cd Wildlife-alert-system
```

2. **Install the required libraries**:
  ```bash
  pip install ultralytics roboflow opencv-python matplotlib
  ```



## **Results 🎯**

**Training Performance**

Confusion matrix

Training metrics


## **Inference Output**


The system overlays bounding boxes on detected animals. Detected images are stored in /content/runs/detect/predict/.



## **Future Enhancements 🔮**

- Expand detection to other species.
- Optimize for real-time video feeds.
- Add SMS alert functionality.
- Integrate with IoT devices for automated deterrent systems.


## **Contributing 🤝**

Feel free to fork the repository and submit pull requests. All contributions are welcome!

## **License 📜**

This project is licensed under the MIT License.



