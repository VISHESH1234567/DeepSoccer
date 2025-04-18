## To download the sample videos  from the [DFL - Bundesliga Data Shootout](https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout) Kaggle competition using gdown.

Create data/test/ directory and in that directory run the following commands

```bash
!gdown -O "0bfacc_0.mp4" "https://drive.google.com/uc?id=12TqauVZ9tLAv8kWxTTBFWtgt2hNQ4_ZF"
!gdown -O "2e57b9_0.mp4" "https://drive.google.com/uc?id=19PGw55V8aA6GZu5-Aac5_9mCy3fNxmEf"
!gdown -O "08fd33_0.mp4" "https://drive.google.com/uc?id=1OG8K6wqUw9t7lp9ms1M48DxRhwTYciK-"
!gdown -O "573e61_0.mp4" "https://drive.google.com/uc?id=1yYPKuXbHsCxqjA9G-S6aeR2Kcnos8RPU"
!gdown -O "121364_0.mp4" "https://drive.google.com/uc?id=1vVwjW1dE1drIdd4ZSILfbCGPD4weoNiu"
```


## Directory Structure

    .
    ├── dataset
    |   ├── roboflow        #for storing dataset used for fine tuning detection model for all 4 classes
    |   ├── roboflow_ball   #for storing dataset used for fine tuning detection model for all 4 classes
    |   ├── roboflow_pitch  #for storing dataset used for fine tuning pose detection yolo model              
    |   └── tests           #for storing samples to be tested and results obtained
    ├── runs                #to store fine tuned model
    │   ├── detect                  
    |   └── pose              
    └── utils