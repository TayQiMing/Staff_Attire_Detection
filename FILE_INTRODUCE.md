### Folders:
- **datasets/**: This folder contains the dataset used for training and testing the model, including images and labels. The data is generated and downloaded from Roboflow.

- **runs/**: In this folder, you store the outcomes of model detections and predictions.

- **csv/**: The CSV folder is used for storing CSV output files generated during various tasks.

- **training_outputs/**: This folder holds the model training outputs for both the 50-epoch and 100-epoch models.

- **\_Documentation/**: This folder contains all the documentation related to the project.

### Notebook Files:
- **Train_Model(Kaggle).ipynb**: This Kaggle notebook is used for training the object detection model.

- **VideoDetect_ModelDeploy(Kaggle).ipynb**: Another Kaggle notebook, it is used for predicting sample videos and deploying the model to the Roboflow website.

- **Run pretrained model(Jupyter).ipynb**: This Jupyter notebook is utilized to use the trained model for predicting sample images and videos.

### CSV Files:
- **50epoch_video_detected_output.csv**: This file contains the detected frame output of a sample video using the 50-epoch model. It includes columns for the video frame number, detected box values (in xywh format), and the total detected nametag count.

- **50epoch_video_total_output.csv**: Similar to the previous file, this one includes the total frame output of a sample video with the 50-epoch model. It also contains columns for the video frame number, detected box values, and the total detected nametag count.

- **model50ep_test_data_output.csv**: This CSV file is an output for a test dataset consisting of 36 images using the 50-epoch model. It includes columns for image paths, image labels (default class value and xywh values), and detected box labels (xyxy coordinate values).

- **model100ep_test_data_output.csv**: Similar to the previous file, this one is the output for a test dataset of 36 images using the 100-epoch model. It contains columns for image paths, image labels, and detected box labels.

