# Satellite-Building-Detection
Detection and recognition houses and buildings on satellite radar images taken by the RadarSAT-2 satellite using the YOLOv4 neural network.


### Table of Contents  
INTRODUCTION ...................................................... 5
 
CHAPTER 1 ANALYZING AND PROCESSING SAR IMAGES ..................... 6

1.1 General information about SAR ......................... 6 \
1.2 Characteristics of SAR images ......................... 9\
1.3 Enhancement and preprocessing of SAR images .......... 10\
1.3.1 Data creation ...................................... 10\
1.3.2 Calibration ........................................ 11\
1.3.3 Multiple views ..................................... 12\
1.3.4 Selecting a region of interest ..................... 13\
1.3.5 Segmentation and classification .................... 13\
1.4 Conclusions on Chapter 1 ............................. 13\

CHAPTER 2 SEARCH AND POSITIONING OF BUILDINGS ON SAR IMAGES ...... 14\
2.1 Characterization of the SAR image dataset ................................ 14\
2.2 Characterization of buildings in SAR images .............................. 15\
2.3 Labeling and data structure for training ................................. 18\
2.4 Definition and training of neural network model for building detection ... 19\
2.4.1 Generating the dataset for the YOLOv4 network .......................... 20\
2.5 Conclusions on chapter 2 ................................................. 21\

CHAPTER 3 BUILDING DETECTION IMPLEMENTATION ON SAR IMAGES ........ 22\
3.1 Data preparation software ............................ 22\
3.2 Training YOLO for building recognition ............... 24\
   3.2.1 Setting up files for training ................... 24\
   3.2.2 Loading pre-trained layers ...................... 25\
   3.2.3 Training the model .............................. 25\
3.3 Testing and quality assessment of the trained model .. 27\
3.4 Conclusions on Chapter 3 ............................. 30\
CONCLUSION ....................................................... 31\
LIST OF SOURCES USED ............................................. 32\
APPENDIX A ....................................................... 33\
APPENDIX B ....................................................... 34\


![image](https://github.com/egbusko/Satellite-Building-Detection/assets/60915234/b2ef66f7-0d0a-43c7-9833-52fa6964a63d)
input image example
