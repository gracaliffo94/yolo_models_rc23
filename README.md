# **YoloV7-based object detection for RoboCup SPL**

**Classes:**

ball
robot
goalpost
goalspot




**Usage:**
1) create environment using python3.8.10 , namely the version we currently have in our nao's OS 

   **python3.8 -m venv venv**
   
2) **venv/bin/python -m pip install -r requirements.txt**
3) for just detection:
   **venv/bin/python detect_m.py**
4) for test and metrics:
   **venv/bin/python test_m.py**

**Other models:**

I'm currently adding trained nnets in the pretrained_weights folder.

However, due to size limits, large models must be downloaded from the following links:

1 - Original YoloV7 Model, 37M params - 10K epochs (.pt containing only the weights) 

https://drive.google.com/file/d/1uI1NK4otw9mRU-B4EKM14A6vCsUSovjD/view?usp=share_link

2 - Custom YoloV7 Model, 177K params  - 10K epochs (.zip containing also stuff related to metrics) 

https://drive.google.com/file/d/1M7ln4Z4uyb5VNgFNw9MLsUa7TvkNMGGZ/view?usp=share_link

**Citation:**
1. Albani, D., Youssef, A., Suriani, V., Nardi, D., Bloisi, D.D.: A deep learning approach for object recognition with nao soccer robots. Lecture Notes in Computer Science (2017)
2. Bloisi, D., Duchetto, F.D., Manoni, T., Suriani, V.: Machine learning for realistic ball detection in robocup spl (2017) 
3. Fang, G., Ma, X., Song, M., Mi, M.B., Wang, X.: Depgraph: Towards any structural pruning (2023)
4. Leiva, F., Cruz, N., Bugueño, I., Ruiz-del Solar, J.: Playing soccer without colors in the spl: A convolutional neural network approach. In: Holz, D., Genter, K., Saad, M., von Stryk, O. (eds.) RoboCup 2018: Robot World Cup XXII. pp. 122–134. Springer International Publishing, Cham (2019)
5. Narayanaswami, S.K., Tec, M., Durugkar, I., Desai, S., Masetty, B., Narvekar, S., Stone, P.: Towards a real-time, low-resource, end-to-end object detection pipeline for robot soccer. In: RoboCup 2022: Robot World Cup XXV, pp. 62–74. Springer (2023)
6. Szemenyei, M., Estivill-Castro, V.: Robo: Robust, fully neural object detection for robot soccer. In: RoboCup 2019: Robot World Cup XXIII  23. pp. 309–322. Springer (2019)
7. Thielke, F., Hasselbring, A.: A JIT compiler for neural network inference. In: RoboCup 2019: Robot World Cup XXIII, pp. 448–456. Springer International Publishing (2019). https://doi.org/10.1007/978-3-030-35699-6 3 6, https://doi.org/10.1007%2F978-3-030-35699-6_36
8. Yao, Z., Douglas, W., O’Keeffe, S., Villing, R.: Faster yolo-lite: Faster object detection on robot and edge devices. In: RoboCup 2021: Robot World Cup XXIV, pp. 226–237. Springer (2022)
9. Faster YOLO-LITE: Faster Object Detection on Robot and Edge Devices. ZhengBai Yao, Will Douglas, Simon O'Keeffe, and Rudi Villing.
https://roboeireann.maynoothuniversity.ie/research/SPLObjDetectDatasetV2.zip
