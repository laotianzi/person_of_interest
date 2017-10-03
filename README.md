# person_of_interest

## **Overview**

This is my fifth (final) project at Metis data science bootcamp. For public safety, I created a machine that spies everything... ok, a system that detects and tracks pedestrians from one of the public cameras at Time Square. So humans do not have to stare at more than 17k public cameras for suspicious moments, but get alerts when there are abnormal higher speed or higher count of people in front of the camera. This is the first time I encountered with computer vision. It was so exiting to see this system built from scratch when I know nothing about OpenCV tracker API and TensorFlow object detection API.

## **Data Source**

The video data is available from [the EarthCam](https://www.earthcam.com/usa/newyork/timessquare/?cam=tsstreet).
The TensorFlow pre-trained models are from [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md).

## **Goal**

The system gives pedestrian moving speed from OpenCV API and counts from TensorFlow object detection API.

## **Approach**

Please visit my [blog post](https://laotianzi.github.io/blog/2017/09/12/Challenge-5-Kojak/) and [Google slides](https://goo.gl/k71BHU) for more detailed information regarding this project's workflow and results.

