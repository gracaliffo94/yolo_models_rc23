YoloV7-based implementation for object detection in RoboCup SPL

Usage:
1) create environment using python3.8.10 , namely the version we currently have in our nao's OS 

   **python3.8 -m venv venv**
   
2) **venv/bin/python -m pip install -r requirements.txt**
3) for just detection:
   **venv/bin/python detect_m.py**
4) for test and metrics:
   **venv/bin/python test_m.py**

Other models:


I'm currently adding trained nnets in the pretrained_weights folder.


However, due to size limits, large models must be downloaded from the following links:


1 - Original YoloV7 Model, 37M params https://drive.google.com/file/d/1uI1NK4otw9mRU-B4EKM14A6vCsUSovjD/view?usp=share_link
