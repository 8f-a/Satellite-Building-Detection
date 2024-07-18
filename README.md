# Satellite-Building-Detection
Detection and recognition houses and buildings on satellite radar images taken by the RadarSAT-2 satellite using the YOLOv4 neural network.\
*Term paper 2021*

---
### Table of Contents  
#### INTRODUCTION
#### CHAPTER 1 ANALYZING AND PROCESSING SAR IMAGES ... 6
1.1 General information about SAR\
1.2 Characteristics of SAR images\
1.3 Enhancement and preprocessing of SAR images\
1.3.1 Data creation\
1.3.2 Calibration\
1.3.3 Multiple views\
1.3.4 Selecting a region of interest\
1.3.5 Segmentation and classification\
1.4 Conclusions on Chapter 1
#### CHAPTER 2 SEARCH AND POSITIONING OF BUILDINGS ON SAR IMAGES ... 14
2.1 Characterization of the SAR image dataset\
2.2 Characterization of buildings in SAR images\
2.3 Labeling and data structure for training\
2.4 Definition and training of neural network model for building detection\
2.4.1 Generating the dataset for the YOLOv4 network\
2.5 Conclusions on chapter 2
#### CHAPTER 3 BUILDING DETECTION IMPLEMENTATION ON SAR IMAGES ... 22
3.1 Data preparation software\
3.2 Training YOLO for building recognition\
   3.2.1 Setting up files for training\
   3.2.2 Loading pre-trained layers\
   3.2.3 Training the model\
3.3 Testing and quality assessment of the trained model\
3.4 Conclusions on Chapter 3
#### CONCLUSION

---

![263457321-8c1b9e98-81b3-4245-9349-a6f007546ede](https://github.com/user-attachments/assets/58d0ea60-4f02-4ee6-b6a1-14a45a1f5137)
![263457326-2c91dfe5-2a4c-4183-8ba6-c0d892f55d55](https://github.com/user-attachments/assets/2fc4d140-747d-4bc7-9019-a1917e3db35d)
![263457329-6920b8ba-c218-4950-bd7b-730ab3dcb3a0](https://github.com/user-attachments/assets/aff52b5a-318a-4068-8275-c8cd4da5d024)
![263457333-0dd85745-73ca-46cc-adfc-2785494382bd](https://github.com/user-attachments/assets/2f1318b6-eb3b-439b-9cd3-724676abf7e1)
![264086541-4df4759b-04e5-41f2-8128-fa058cc8e4d6](https://github.com/user-attachments/assets/60c0c0b1-67c1-4a31-8f3a-c7a5b03fcdf6)
![263457342-4c6a0d88-eada-4c53-afd5-348e3fd57a67](https://github.com/user-attachments/assets/089c8e6b-eeb1-4fe9-a773-f067e3cba626)
![263457348-f0fb99e1-980f-4025-881d-b1c149ab8d47](https://github.com/user-attachments/assets/5c136cb0-295c-46f5-a8c5-9b8cc573d6c6)
![263457352-4da4c007-4eac-45d8-877a-1707514206b6](https://github.com/user-attachments/assets/6b5291e8-1f18-4c34-8617-226c215bba8d)
![263457360-ffc5d85a-2c28-4303-9416-cc1058806595](https://github.com/user-attachments/assets/82b2ce2f-cd61-4d4e-ad3e-3a7b954534d8)
![264086812-f1db72ba-6d8c-4dff-812f-e1ad7d85faaa](https://github.com/user-attachments/assets/b2c82c92-4a6d-4aa0-8258-4c402375d51e)
![263457367-94638892-17f4-4e5c-b650-0c8d5d64c25a](https://github.com/user-attachments/assets/2bfdb265-13ed-4c8b-b570-4dea21db6c3a)


