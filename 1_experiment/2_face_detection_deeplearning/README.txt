#Activate your Virtual Environment
workon OpenCV-master-py3
workon py3cv4

#How to execute: 
python detect_faces_video.py --prototxt deploy.prototxt.txt \
	--model res10_300x300_ssd_iter_140000.caffemodel

#Deactivate Virtual Environment
deactivate

#reference: 
#https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/

