# duality-ai-hackathon
YOLOv8-based object detection project using synthetic space station data

# Duality AI Hackathon – Space Station Object Detection

This project was built for the Duality AI Hackathon, using synthetic data to train an object detection model (YOLOv8) on critical space station tools.
 Problem Statement

Space stations pose tough visual environments with low lighting, occlusions, and tight spaces — making object detection difficult.

objective

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
- Final mAP@0.5: **91.8%**




## EVA Guardian – App Concept

A safety-check assistant that uses the trained model to verify presence of essential tools.
EVA Guardian uses real-time object detection to verify the presence of critical tools (like fire extinguishers or oxygen tanks) before astronauts exit the station. It provides visual confirmation and alerts if any item is missing.

##  Folder Structure (could not upload one folder because of size issues)
main/
├── ENV_SETUP/
│ └── install_packages.bat
├── train.py
├── predict.py
├── visualize.py
|__ yolo_params.yaml
|__space_station_flask_app.zip
        |__app use report
        |__video link.txt(gdrive)
        |__video file demo
├── classes.txt
|__result.jpg
|__confusion matrix.jpg
|__best.pt
|__screenshot of work when processed
|__EVA Guardian ppt.pdf



##  Model Performance

| Metric            | Value  |
|                   |        |
| mAP@0.5           | 91.8%  |
| mAP@0.5:0.95      | 79.8%  |
| Precision         | 96.0%  |
| Recall            | 85.1%  |


## Submission Info

-  GitHub Repo: [click here to open Github repo](https://github.com/prii12345/duality-ai-hackathon.git)
-  ZIP Download: [Download ZIP](https://github.com/prii12345/duality-ai-hackathon/archive/refs/heads/main.zip)
  
##  “how to use” block:

# 1. Install requirements
bash ENV_SETUP/install_packages.bat

# 2. Run inference (example)
python predict.py --source path/to/image.jpg

# 3. Train (if data available)
python train.py  


## Notes
- due to Github file soze limits the full dataset has not updated.
- Model was trained using CPU and official Falcon-provided training scripts.
- All setup followed the official instructions from Hackathon PDF.


## Continuous Learning with Falcon

New synthetic data can be generated via Falcon → fine-tune model → re-deploy with improved accuracy.


 Team

Team Name:Innovators
Priyanka Yadav : priyanka941677@gmail.com ( ai engineering, documentation & presentation)
kirti gupta : mail.kirtigupta12@gmail.com (bonus use case proposal)
Darshita:darshita2591@gmail.com ( documentation)
Institute:ipcw




