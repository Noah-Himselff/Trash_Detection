# Trash_Detection
**Overview**
This repository contains the code and resources for a YOLOv8-based trash detection model. The model is trained to identify and localize various types of trash objects in images and videos.
This project was initiated in collaboration with the Municipality of Tehran requested by Petropalatoos located in Iranian National Research Rnstitute of Petroleum Industry(RIPI), aiming to address the challenge of trash detection within the city. The Municipality of Tehran served as the original client for this program, providing valuable insights and requirements to tailor the solution to the specific needs of the city.


**Dataset**
The dataset consists of over 2400 images collected from diverse sources, including other datasets, web scraping, and real-world photos. Each image is labeled with bounding boxes around trash objects using the Roboflow platform.

**Training Process**
Labeling: Bounding boxes were created and annotations added to the dataset using the Roboflow website.
Data Preparation: The Roboflow library was utilized to access and organize the annotated dataset.
![Image Alt Text](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg3fH2YX7U79s6s7RHZJuPlYJcqkc8PB1mGwD5wPlmom2yh3q-3y3vAoaopZ0U-a7RfCAZNCk7KBKt1RDq2refpSuF50oj6vcg6mtEuQP7UwwgodufA2HKB0czwHW1SMSt1uVcsIOH2dfa2Rc6cOqzSR6pmC4YXJW_tHD5LND9j2UszTUYCkn-6kjlH/s1600/Roboflow%20blog%203.png)

Model Integration: Ultralytics library was employed to seamlessly incorporate YOLOv8s into the project.
Fine-Tuning: YOLOv8 was fine-tuned on the annotated dataset for 100 epochs, resulting in a model with promising performance.

**Model Performance**
mAP 50: 73.5%

Recall (R): 68.6%

Precision (Box): 74.8%

**License**
This project is licensed under the MIT License - see the LICENSE file for details.

**Contact**
For any inquiries or collaborations, feel free to contact [hosseinseyyedi2038@gmail.com].
