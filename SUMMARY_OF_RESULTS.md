# *SUMMARY OF RESULTS:*<br />

1) First step is to analize or convert point clouds in a complete image:

![alt text](https://github.com/HomeBrain-ARG/SDCE_Mid-Term-Project_3D-Object-Detection/blob/main/01_Results/ID_S1_EX1_Range_Image_Channels/20221016_ID_S1_EX1_range_image_screenshot_16.10.2022.png)<br />

2) After several analysis of Bird Eye View we can see in the LiDAR point clouds that you will find several vehicles in the road:

![alt text](https://github.com/HomeBrain-ARG/SDCE_Mid-Term-Project_3D-Object-Detection/blob/main/01_Results/ID_S1_EX2_Lidar_Point_Cloud/20221016_ID_S1_EX2_3D_Point%20Cloud_6-Vehicles_Marked.png)<br />

3) The intensity map in a conversion of Bird Eye View to (X,Y) image in order to use it to detect, for example: vehicles:

![alt text](https://github.com/HomeBrain-ARG/SDCE_Mid-Term-Project_3D-Object-Detection/blob/main/01_Results/ID_S2_EX2_BEV_Intensity_Map/20221017_BEV_Intensity_Map.png)<br />

4) Taking advantage of the BEV we can analyze the intesity of the LiDAR beam/beams collision in order to improve the object detection:

![alt text](https://github.com/HomeBrain-ARG/SDCE_Mid-Term-Project_3D-Object-Detection/blob/main/01_Results/ID_S2_EX3_BEV_Map/20221017_BEV_Height_Map.png)<br />

5) Keep in mind that BEV views are 3D, for this reason you can navigate in depth and breadth:

![alt text](https://github.com/HomeBrain-ARG/SDCE_Mid-Term-Project_3D-Object-Detection/blob/main/01_Results/ID_S1_EX2_Lidar_Point_Cloud/20221016_ID_S1_EX2_3D_Point%20Cloud_6-Vehicles.png)<br />

6) SOme metrics indicating FN, FP, Precision and Recall:

![alt text](https://github.com/HomeBrain-ARG/SDCE_Mid-Term-Project_3D-Object-Detection/blob/main/01_Results/ID_S4_EX2_FN_and_FP/20221017_BEV_Object_Detection_Eval_FP-FN.png)<br />

![alt text](https://github.com/HomeBrain-ARG/SDCE_Mid-Term-Project_3D-Object-Detection/blob/main/01_Results/ID_S4_EX3_Precision_Recall/20221017_Eval_BEV_Precision-Recall.png)<br />

