# Shot2Tactic-Caption

> 📢 **News:**  
> Our paper **"Shot2Tactic-Caption: Multi-Scale Captioning of Badminton Videos for Tactical Understanding"** has been **accepted at ACM MMSports 2025** 🎉  

## 🏗️ Model Architecture

![Model Architecture](https://raw.githubusercontent.com/Ning-D/Shot2Tactic-Caption/main/figures/model_architecture.png)




## 🧩 Dataset
### 📁 Structure

````text
Shot2Tactic-Caption/
├── videos/                 # Raw video clips for each match
│   ├── match1/
│   │   ├── clip_001.mp4
│   │   ├── clip_002.mp4
│   ├── match2/ ...
├── annotations/            # Annotation files for each data split
│   ├── train.json
│   ├── val.json
│   ├── test.json
├── tactic_units/           # Definitions of tactic templates and state transitions
│   ├── tactic_templates.json
└── README.md               # Dataset documentation

## 📥 Dataset Download

The **Shot2Tactic Dataset** can be downloaded from the following link:

- [📂 Google Drive (Shot2Tactic-Caption Dataset)](https://drive.google.com/your_dataset_link_here)

> ⚠️ **Note:** This dataset is released for research purposes only. Please cite our paper if you use it in your work.
