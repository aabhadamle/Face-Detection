## 📸  Face Detection using OpenCV

### Overview

This project demonstrates real-time face detection using computer vision techniques. It uses the **YOLOv8 (You Only Look Once)** object detection model from the Ultralytics library. The model is trained and evaluated using a custom dataset obtained via **Roboflow** . It detects human faces from images (e.g. uploaded images).

### Files in the Repo

face-detection.ipynb – Notebook containing the face detection code.

README.md – Project overview and usage guide.

### Features

- Custom dataset download and setup from Roboflow
- Training a YOLOv8 model on the dataset
- Evaluation of model performance
- Visualization of predictions on validation images
- Draws bounding boxes around detected faces.

### Technologies Used
- Python 3

- Kaggle Notebook

- [Ultralytics YOLOv8](https://docs.ultralytics.com/)

- OpenCV

- IPython display for showing predictions


### How to Run

#### 1. Run Locally

Clone the repository:

`git clone https://github.com/your-username/your-repo-name.git`
`cd your-repo-name`
Install the required packages:

`pip install ultralytics notebook`
Launch Jupyter Notebook:

`jupyter notebook`
Then open and run face-detection.ipynb.

#### 2. Run on Kaggle
1. Go to https://www.kaggle.com/

2. Create a new Notebook

3. Upload the file: face-detection.ipynb

4. Run all the cells

###  Notes

You can replace the input image source as per your needs.

### License
This project is open-source and available under the MIT License.
