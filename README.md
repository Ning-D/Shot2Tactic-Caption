# Shot2Tactic-Caption

> 📢 **News:**  
> Our paper **"Shot2Tactic-Caption: Fine-grained Video Captioning for Tactical Understanding in Racket Sports"**  
> has been **accepted at ACM MMSports 2025** 🎉  


## 📂 Dataset Structure

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

