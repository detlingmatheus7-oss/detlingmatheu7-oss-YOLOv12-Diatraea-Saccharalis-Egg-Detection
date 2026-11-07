# detlingmatheu7-oss-YOLOv12-Egg-Detection
Repository containing the source code and dataset used to generate the YOLOv12 and RT-DETR models for my undergraduate research project.
To reproduce the experiment, you must download the images and labels from train and val, the images and labels must have matching names example: 01.png must have a 01.txt.
As Colab uses your google drive you must give the used path in the config.yaml file, both the validation and train folders in images folder must have a matching validation and train folders in a labels folder, which contains the .txt files. 
The first colab block must be executed to give access to your Google Drive.
The next five blocks should be executed in sequence.
Note: The fourth block is used to clear old models and cache; if no models exist, simply comment out the fourth line.
The seventh block is used to generate augmentations.
The final three blocks are used to test the model generated in the fifth block.
Code instructions are valid for both YOLOv12 and RT-DETR codes.
