# Real-time monitoring of falls in the elderly

The task will be to carry out the monitoring of falls in elderly people aiming at a more immediate and adequate help.



## About Project Showcase

It is based on the [Intel® distribution of OpenVINO™ toolkit]( https://software.intel.com/en-us/openvino-toolkit). OpenVINO (Open Visual Inference and Neural network Optimization) is a free toolkit facilitating the optimization of deep learning models and deployment onto Intel hardware.
This Project Showcase will work with 2D pose estimation algorithm using the pre-trained model [human-pose-estimation-0001]( https://docs.openvinotoolkit.org/2019_R1/_human_pose_estimation_0001_description_human_pose_estimation_0001.html), which is a human pose estimation network, that produces two feature vectors. The algorithm uses these feature vectors to predict human poses. For every person in an image, the network detects a human pose: a body skeleton consisting of keypoints and connections between them.
The pose may contain up to 18 keypoints: ears, eyes, nose, neck, shoulders, elbows, wrists, hips, knees, and ankles.

Other material:
- Video/Camera as inputs, via OpenCV*
- Raspberry pi 4



## How to run the project

The application will read command line parameters and loads human pose estimation model. Upon getting a frame from the OpenCV VideoCapture, the application executes human pose estimation algorithm and displays the results.
To run the demo, you can use public or pre-trained models. To download the pre-trained models, use the OpenVINO [Model Downloader and other automation tools]( https://docs.openvinotoolkit.org/latest/_tools_downloader_README.html) or go to https://download.01.org/opencv/. Before running the demo with a trained model, make sure the model is converted to the Inference Engine format (*.xml + *.bin) using the Model Optimizer tool.



## To do inference on a CPU, run the following command in this link:

[Use the Model Downloader and Model Optimizer for the Intel® Distribution of OpenVINO™ Toolkit on Raspberry Pi*](https://software.intel.com/en-us/articles/model-downloader-optimizer-for-openvino-on-raspberry-pi)
