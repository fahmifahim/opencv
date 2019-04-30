#Activate your Virtual Environment
workon OpenCV-master-py3

#How to execute: 
python recognize_video.py --detector face_detection_model \
	--embedding-model openface_nn4.small2.v1.t7 \
	--recognizer output/recognizer.pickle \
	--le output/le.pickle

#Deactivate Virtual Environment
deactivate

#reference: 
#https://www.pyimagesearch.com/2018/09/24/opencv-face-recognition/
