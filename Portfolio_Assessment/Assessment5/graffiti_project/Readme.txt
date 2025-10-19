=============================================================
COS40007 - Portfolio Assessment 5: Deep Learning using YOLO v5
=============================================================

Student: Nguyen Quy Hung

PROJECT STRUCTURE:
-----------------
1. Week6.ipynb - Main code containing all steps
2. iterations/ - Contains results for each training iteration
   - Each iteration folder has:
     * best.pt - Trained model weights
     * results.csv - Test results with [image_name, confidence, IoU]
     * samples/ - 2 best detected images with bounding boxes
3. video_results/ - Graffiti detection on 5 videos

Link : https://github.com/S1zzX/COS40007-Artificial-Intelligence-for-Engineering-/tree/main/Portfolio_Assessment/Assessment5
=============================================================
Storage Location Structure:
│
├── Readme.txt                         
│
├── dataset\                           
│   ├── images\
│   │   ├── train\
│   │   └── test\
│   ├── labels\
│   │   ├── train\
│   │   └── test\
│   └── data.yaml
│
├── iterations\                         
│   │
│   ├── iteration_1\
│   │   ├── best.pt                 
│   │   ├── results.csv             
│   │   ├── samples\                
│   │   │   ├── sample1_iou0.XXX_conf0.XXX.jpg
│   │   │   └── sample2_iou0.XXX_conf0.XXX.jpg
│   │   ├── train\
│   │   │   ├── weights\
│   │   │   │   ├── best.pt
│   │   │   │   └── last.pt
│   │   │   └── results.csv
│   │   └── detect\
│   │       └── test\
│   │           ├── [40 detected images]
│   │           └── labels\
│   │
│   └── iteration_N\...
│
├── videos\                              
│   ├── video1_graffiti_door.mp4
│   ├── video2_busy_street.mp4
│   ├── video3_train_station.mp4
│   ├── video4_wall_marker.mp4
│   └── video5_street_art.mp4
│
└── video_results\                   
    ├── video1_graffiti_door.mp4
    ├── video2_busy_street.mp4
    ├── video3_train_station.mp4
    ├── video4_wall_marker.mp4
    └── video5_street_art.mp4