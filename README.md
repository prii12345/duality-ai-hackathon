# duality-ai-hackathon
YOLOv8-based object detection project using synthetic space station data

# Duality AI Hackathon – Space Station Object Detection

This project was built for the Duality AI Hackathon, using synthetic data to train an object detection model (YOLOv8) on critical space station tools.
 Problem Statement

Space stations pose tough visual environments with low lighting, occlusions, and tight spaces — making object detection difficult.

 Objective

- Train a YOLOv8 model to detect:
  -  Toolbox  
  -  Fire Extinguisher  
  -  Oxygen Tank
- Handle visual challenges
- Build a safety-check app for astronauts
- Enable continuous improvement via Falcon

 Model & Training

- YOLOv8s used with 3-class synthetic dataset
- 5 epochs, trained on CPU
- Final mAP@0.5: **91.4%**




## EVA Guardian – App Concept

A safety-check assistant that uses the trained model to verify presence of essential tools before astronaut EVAs (spacewalks).

##  Folder Structure
HackByte_Dataset/
├── data/
│ ├── train/
│ ├── val/
│ └── test/
├── ENV_SETUP/
│ └── install_packages.bat
├── train.py
├── predict.py
├── visualize.py
├── yolo_params.yaml
├── classes.txt
└── runs/
└── detect/
└── train/
├── labels.jpg
├── confusion_matrix.png
└── weights/

---

##  Model Performance

| Metric            | Value  |
|-------------------|--------|
| mAP@0.5           | 91.4%  |
| mAP@0.5:0.95      | 79.8%  |
| Precision         | 96.0%  |
| Recall            | 85.1%  |

---

## Submission Info

- 🔗 GitHub Repo: https://github.com/prii12345/duality-ai-hackathon.git)
- 📦 ZIP Download: [Click here to download ZIP](https://github.com/yourusername/your-repo/archive/refs/heads/main.zip)
- 📄 Report: Included inside `HackByte_Dataset/Report.pdf`
  


## Notes

- Model was trained using CPU and official Falcon-provided training scripts.
- All setup followed the official instructions from Algoverse Hackathon PDF.


## Continuous Learning with Falcon

New synthetic data can be generated via Falcon → fine-tune model → re-deploy with improved accuracy.


 Team

Team Name:ByteStack
Team Leader: Priyanka Yadav  
Email:priyanka941677@gmail.com 
Institute:ipcw




