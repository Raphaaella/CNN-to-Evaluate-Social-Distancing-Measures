# CNN-to-Evaluate-Social-Distancing-Measures
Project for the seminar "Deep Learning for Social Sciences": This project explores the application of Convolutional Neural Networks (CNNs) to evaluate social distancing measures using surveillance and crowd imagery. By leveraging advanced CNN architectures, students will develop models capable of detecting and assessing adherence to social distancing guidelines in public spaces.  

## Folder Structure

### 01_code

This folder contains all the code we wrote for preprocessing and carrying out the analysis.

* [0_Scraping](01_code/0_Scraping) Scrapes images from the Earthcam webpage for a specified time window.
* [1_Preprocessing](01_code/1_Preprocessing) Contains all preprocessing steps such as downloading COCO and Oxford images, resizing images and     bounding boxes, preparing data for YOLO format. It also contains a preliminary data analysis.
* [2_Count_CNN_Model](01_code/2_Count_CNN_model) Here the code for building the Count CNN Model is stored. The model is built, evaluated and its weights are saved in this folder. It also contains a file for visualizing intermediate feature maps.
* [3_YOLO](01_code/3_YOLO) All the code for building and evaluating the YOLO model on the data. YOLO model is finetuned on images from the Oxford Street Centre Dataset. All evaluation files the model outputs based on this fine-tuning are saved here.
* [4_Analysis](01_code/4_Analysis) The code for analyzing both the Count CNN and the YOLO model is stored here.

### 02_data

We stored all our main data source on Google Drive due to the upload limit of GitHub. For this reason, we have only saved very small files here.

* [annotations](02_data/annotations) These are manually created annotations for the Earthcam images from London, New York and New Orleans we created for evaluation purposes.

### 03_literature

Here you can find all papers we are citing in the report in pdf format.

### 04_presentation

This folder contains the PowerPoint presentation of the project as a pdf.

### 05_report

Here you can find the project report.