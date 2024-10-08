# CRNN-CTC algorithm for Amharic braille document lina image recognition
## This is detail about the dataset used to train the proposed algorithm. 
![image](https://github.com/user-attachments/assets/90825f47-293e-431b-99f2-208eb82e1352)

## Authors: Nega Agmas Asfaw and Birhanu Hailu Belay
### Dataset Details
This dataset was created for the fisrt time and made available online for free to researchers working on Amharic Braille document recognition. We have collected Braille documents from AAU-Kennedy library, Addis Ababa, Ethiopia. The documents include both typewritten and manually produced one sided documents, most of which are typewritten and noisy. For the variability of label sequences, the documents include the contents that deal for history of Ethiopia, law, agriculture and health, which are collected from real life degraded documents and scanned in low resolution (200dpi) using flat-bed scanner.  </br>   </br>
The dataset contains 2100 Amharic Braille document Line-images, in which 2000 line-images are for training and 100 line images for testing with the corresponding Ground-Truth (GT) labels. Line-images are stored in grayscale with .Png file format and named with numbers starting from 0001 with their equivalent line number in the label text , and 248 characters have been included in the labels. For example: text in the first line of label.txt is transcription for image 0001.png(first image) in line images folder, and so on.   </br>   </br>
The goal of creating this dataset was to alleviate the dearth of resources for this underserved language and to encourage researchers to focus on sequence-to-sequence deep learning algorithms, which reduce the need for detailed pre and post processing in OBR systems. The dataset was examined using the algorithm we proposed, and the results were satisfactory without the requirement for pre- and postprocessing. </br></br></br>
You can use the following link to download the dataset.  
[Train Data.rar](https://drive.google.com/file/d/1joI4cHd7C5LE1uM970p_RPM5QtJK99zK/view?usp=sharing).
[Test Data.rar](https://drive.google.com/file/d/16k2_Lf7SaCO5pHbTGOdtlKxbG0fvgvzm/view?usp=sharing) </br>   </br>


The implementation for the proposed algorithm is also attached in this repository with name Impelemtation.ipynb </br> </br>
If you need further about the dataset and Author information, Visit my personal website: [My Website](https://sites.google.com/view/nega-agmas/home)
