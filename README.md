# Traffic Signs Identifier - Data Centric AI
This project contains the modules responsible for the traffic sign identification tool using the DCAI paradigm. 
It provides utensils to expand the dataset by integrating existing datasets and extracting new samples from video files, and to enhance the dataset by augmentation and undersampling. 
Three submodules have been distincted:
- [DFG to YOLOv5 converter](https://github.com/PCiesielczyk/DFG_to_yolov5_converter) - provides tools for converting labels and extracting Traffic Sign samples from DFG dataset to YOLOv5 format.
- [TS samples extractor](https://github.com/PCiesielczyk/TS_samples_extractor) - an application for detecting traffic signs from a video file, labeling them and saving in dataset.
- [Traffic Signs Identifier](https://github.com/PCiesielczyk/TSI) - an application for detecting and classifying traffic signs from image and web camera. It also includes utensils for preparation and preprocessing of dataset and model training.
