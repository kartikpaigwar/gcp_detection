#Automatic GCP Marker Detection and locating GCP

#Detailed Approach has been explained in Automatic_GCP_detection_approach.pdf 

#Requirement:
 1. python3
 2. pytorch
 3. opencv2
 4. cuda

#to_run_model1  $ python3 main1.py

 This performs good with less false predictions. But unable to detect very small GCP markers of size less than 16x16.

#to_run_model2  $ python main2.py			
 
 This performs relatively better. But False predictions are more than model 1.

Tests are performed on 
1. CV-Assignment-Dataset
2. ML - Dataset #2  
(Link to Download https://drive.google.com/drive/folders/1V72hs79YpWrfg3h6s4wYS9Erb0ZdLtEV)

GCP marker are highlighted by Blue rectangle and GCP is located by Red point in the image

Results are located in folder
1. CV-Assignment-Dataset-Output
2. CV-Assignment-Dataset-Output-model2
2. ML - Dataset #2-Ouput      
